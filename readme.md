# Flights in US
## by Vladimir Ploshay


## Dataset

> Full Dataset contains information about flights in United States, including carriers, arrival and departure delays, and reasons for delays, from 1987 to 2008. I my exploration I use only the last year of the dataset - year 2008. The data is taken from http://stat-computing.org/dataexpo/2009/the-data.html provided by American Statistical Association. I used data wrangling in following situations:
- Merging main dataset with carriers' names on their code.
- Changing too long companies' names to make it shorter and visually appealing on graphs.
- Extracting hour from departure and arrival time.


## Summary of Findings

> My findings can be devided into two categories:
> 1)Flights cancellations in general.
- Throughout a year number of flights is almost equally distributed.
- Day of the week has an impact on flights number.
- Flight cancellations have peaks and plateaus during the year.
- April has untupically high number of cancellations by carrier.
- The reason for increase of cancellations by carrier were problems of American Airlines, which failed safety checks.
- Weather delays are much more unpredictable than carriers delays. From April till August and in October-November there is a low number of delays due to weather reasons.
- Security is a very rare cause of flight cancellations. Only 12 cases such cases in 2008.
- The day with biggest cancellation rate has 55 times higher cancellation percentage than the day with lowest cancellations.
- Throughout the year weather is a main reason for cancellations in January-March, September, December.
In other months carrier is the dominating cause of flights cancellations.
- Very few flights arrive or depart from 0 to 7 AM.
> 2)Carrier based cancellations analysis.
- Flights distributions is multimodal. Cancelled flights have a unimodal distribution.
- Southwest Airlines is the biggest carrier in 2008 and has twice more flights than the nearest competitor. However, it has smaller proportion of cancelled flights than some of its competitors, that is why Southwest isn't leading the list of companies by number of cancelled flights in 2008.
- Passangers of flights are affected by multiple cancellation reasons in different proportions. 
- With increasing distance both number of flights and number of cancelled flights are declining. This relationship isn't very strong, however, a visible one.
- Total number of flights is much more stable than number of cancelled flights. Cancelled flighs have outliers that are multiple times bigger than regular numbers.



## Key Insights for Presentation

> I have covered a lot of information about flight and their cancellations in general. Nevertheless, for me carrier based exploration is a bit more attractive.
- I select graph on scheduled and cancelled flights distribution as a first point of my presentation. I used logariphmic transformation to make conclusions more obvious. It is interesting that scheduled flights and cancelled flights are different by mode. One is bimodal and other is a multimodal one. In addition cancelled flights histogram show that cancelled flights is a right skewed distribution and scheduled flights is an opposite - left skewed distribution.
- Second plot I use is a scatter plot. There is a negative relationship between distance and a number of flights (both scheduled and cancelled). Correlation between two parameters isn't strong, in both cases about -0.33%.
- Futher I show difference in cancellation reasons by carrier using pointplot. It also shows a distribution of each cancellation reason by carrier across the year.
- I finalize my presentation with boxplot. Total number of flights is much more stable than number of cancelled flights. Cancelled flighs have outliers that are multiple times bigger than regular numbers.