# kickstarter-analysis

## Deliverable 1 - Overview

The purpose of Deliverable 1 was to determine whether there was a correlation between the outcomes (successful, fail, canceled) of Theater Kickstarters and their respective launch dates. In order to perform this analysis, I created a pivot table which shows the count of outcomes relative to month in which the theater Kickstarter campaigns were launched. 

## Deliverable 1 - Analysis and Challenges

From the Pivot Table we can see, for example, a total of 96 campaigns were launched in the month of January. Of those 96, 7 were canceled, 33 failed, and 56 were successful. In order to visualize this data, I also added a Pivot chart containing a stacked line graph. From this graph, we can see that there is a spike in successful outcomes for theater Kickstarter campaigns in the month of May and stays relatively high through July. It is important to note, however, that the months May - August show much higher Grand Total campaigns compared to other months. 

Overall, I had a pretty easy time with Deliverable 1 since much of the work was already done in the learning module. I do think it would be interesting, however, to dig deeper and find possible reasons as to why there is such a spike in May. Furthermore, I also believe it's important to look at this more longitudinally as opposed to just averaging out the totals across many years so we can get a better understanding of the data. For example, what would the "normal" distance between the successful and failed lines be? If we were to look at the steady decline from May - July would all 4 of those months be significantly above the "normal" distance between successful and failed outcomes? 

## Deliverable 2 - Overview

For this project I was to create a new worksheet that showed the number of successful, failed, and canceled outcomes of play Kickstarter campaigns based on the goal amount. To do this I needed to use the COUNTIFS formula in Excel.

## Deliverable 2 - Analysis and Challenges

From both the table and the line graph we can see that the total number of canceled campaign for the "plays" subcategory was zero across all goal levels. This means that the 100% of the capaigns either succeeded for failed, thus resulting in a mirrored line graph. In other words, when successful campaigns rise, failures fall and vice versa. 

One of the primary challenges I faced during this challenge was actually stumbled upon when I was typing up this README. I did not notice in the instructions that Deliverable 2 was isolated the "plays" subcategory. As a result I had to change my formulas in order to isolate that variable, and not look at the entire Kickstarter worksheet. Before this however, I was having trouble understanding how to use the COUNTIFS formula in order to produce my data table. Instead I used the COUNTIF formula to generate the data by using the upper COUNTIF and subtracting the lower portion. For example, for the 1000 to 4999 goal data, I used the formula =COUNTIF(Kickstarter!$D:$D,=>4999) - COUNTIF(Kickstarter!$D:$D,<1000), which I thought was pretty clever. Although, since I had a new condition to add I figured it would be easier to learn the COUNTIFS function. 
