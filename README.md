# Evaluating Social Mobility in Dallas and Baltimore based on individual income, job density, and average job growth 

## Background 
Social mobility has been a persistent theme throughout US history, reflecting Americans’ collective belief in their country being a “land of opportunity,” a society that provides equal opportunities for individuals from poor and rich families alike. While this belief is widely held among the public, little is known about how mobility opportunities and outcomes have changed over time and what are they being affected by. Based on the open data from Opportunity Insights group, we will analyze how job density in certain area might have affected individuals, recent college graduates to be more precise, to change their social status.  

## Business Question
Compare and contrast two cities, Baltimore and Dallas, with different job density, income, and job growth metrics and create an index to compare Baltimore and Dallas social mobilty.   

## Data Question 
Is job density in the area important to the social status of the people living in that ara or there is no correlation between the two at all?


## Data Analysis

We'll use open data from one source:

Opportunity Insights: The Opportunity Atlas answers this question using anonymous data following 20 million Americans from childhood to their mid-30s which allows to trace the roots of today's affluence and poverty back to the neighborhoods where people grew up. It is a comprehensive Census tract-level dataset of children’s outcomes in adulthood using data covering nearly the entire U.S. population. For each tract,  estimate children’s outcomes in adulthood such as earnings distributions and incarceration rates by parental income, race, and gender are estimated.  Following metrics from the datasets were analyzed:

Job density
Individual income 
Average job growth 

### Analysis
From the dataset 'cty_allIndicators_allSubgroups.csv' values for individual incomes, job density, average job growth were extracted. Data was filtered and sorted and pivot tables were created to evaluate differences between Baltimore and Dallas. Two cities were evaluated on average individual incomes, job growth by counties, and job density in the counties. Baltimore and Dallas were compared on aforementioned metrics and comparison data was summarized on the table.  Social mobility index was created and both cities were assigned indices on how socially mobile they are. 

This analysis compares social mobility between two cities using following variables:

Average individual income:

![](https://github.com/DurdonaG/compare-baltimore_dallas_social_mobilities/blob/main/Images/Project1.2%20.png)

Average job growth: 

![](https://github.com/DurdonaG/compare-baltimore_dallas_social_mobilities/blob/main/Images/Project1.3.png)

Average job density:

![](https://github.com/DurdonaG/compare-baltimore_dallas_social_mobilities/blob/main/Images/Project1.4.png)

Final Analysis: 

![](https://github.com/DurdonaG/compare-baltimore_dallas_social_mobilities/blob/main/Images/Project1analysis.png)


### Interpretation/ Conclusion 
 
To conclude, we can compare our calculated index to Opportunity Insights index based on following factors: 
- factors associated with strong upward mobility from Opportunity Insights:
less segregation by income and race;
lower levels of income inequality;
better schools;
lower rates of violent crime; and
a larger share of two-parent households.

- factors associated with strong social mobility from Our Findings:
Job density rate in the area; 
Individual Income; 
Average Job growth /rates


Following metrics were chosen since based on job density we can tell about the economic growth of the city. Talking social mobility is easy; addressing it is hard. 
Taking about social mobility in a granular level by analyzing each factor seperately lets to get closer to tackling the solution and better understanding the problem. When the debate turns to solutions it too often gets mired in detail, the tinkering and tweaking of policies unlikely to transform society. 






