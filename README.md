# Flights Delay Exploratory Analysis
## by Charles Ikenna Abara


## Airline on-time performance dataset

>This dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from 1987 to 2008. You can see the database description [here](https://www.transtats.bts.gov/DatabaseInfo.asp?QO_VQ=EFD&Yv0x=D). I will be working with Airline on-time performance data from 2004 to 2006. I will perform Exploratory data analysis on the data in order to identify flight patterns/trends and also analyse flights delay and the various causes. A flight is considered delayed when it arrived 15 or more minutes than the schedule. Delayed minutes are calculated for delayed flights only.

## Findings

> **Univariate Exploration:**<br>
After performing univariate exploratory data analysis on the dataset, it was discovered that most flight delays are short and longer flight delays are usually heavy loaded. We also learned that 75.8% of flights during the analysed period arrived on time while 22% were delayed.

> **Bivariate Exploration:**<br>
Ater the bivariate explorotory data analysis we were able to identify the busiest airports, busiest weekdays, the busiest day of the month, the best and worts airports/carriers for delays and the best and worst time of the week, month and year to minimise delays. We also explored how the causes of delays correlate with each other and the total arrival delay using a heatmap and pairplot. Flight cancellations was also looked into and it was found that cancellation caused by Airline/Carrier issues were accounted for majority of cancelled flights(43.9%). Finally the data grouped and the delays for uniquecarriers/airlines was investigated.

> **Multivariate Exploration:**<br>
Finally i used a stacked barplot to dipict how the different causes of delay contribute to the arrival delay of airline carriers.<br>
The heatmap showing the correlation between causes of delays and arrival delays will be used in my explanatory analysis along with the time series plots showing the best and worst periods for delays.



## Key Insights for Presentation

> The cleaned data had over 30 million entries. At the end of the process I was able to visualize the destribution of flight delays and explore relationships between several features. The arrival flight delay destribution showed that most flight delays are short. The different causes of delay seem to me intertwined but the analysis did not establish any direct relation amongs them. Finally, I explored the nature of arrival delays for different airports and airlines.