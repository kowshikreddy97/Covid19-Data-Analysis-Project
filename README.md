I Preprocessed & merged COVID-19 and World Happiness datasets using Python, achieving 95% data accuracy and improving impact assessment clarity by 30% through key metric analysis, leading to actionable
Insights. 

Q: Is there any relationship between corona spread and the happiness in a country?

Deleted the useless columns (using drop, axis=0 means deletes rows, axis=1 means deletes columns), performed aggregation (by country), utilized derivative curves to understand the difference between day to day cases. 
Found the max infection rate. 
From covid 19 - I took 2 columns - country and the max infection rate. 

Imported happiness dataset, dropped useless columns, changed the indexes.

Joined both data sets. 

Created a correlation matrix to find out which features are correlated. 

I have used Seaborn for visualization and to elucidate complex data relationships. 

Created Plots to explore the relationships and impacts: 
 - GDP Vs MAX infection rate
 - Social support vs max infection rate
 - Health life expectancy vs max infection rate
 - Freedom to make like choices vs max infection rate
