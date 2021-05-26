# PyBer Analysis
## Overview
The purpuose of this project was to use data from ride transactions to generate insights about the differences between various types of markets (urban, suburban, or rural). 

## Results
The analysis revealed that there is an apparent relation between city type, number of rides, number of drivers, and average fare. The more densely populated areas tended to have lower average fares, more drivers, and more rides than the less densely populated ones (where urban areas are assumed to be more densely populated than suburban ones, which are assumed to be more densely populated than rural ones). This relation is most clearly depicted in the following scatter plot.
![Fig1 (Full)](https://user-images.githubusercontent.com/80861610/119690365-9ea3eb00-be17-11eb-9a21-154d870099c6.png)

Separating these three variables, we can see how the city type was related to each of these variables respectively. Below are box plots depicting the statistical summaries for city type vs. ride count, fare, and driver count. The relative locations of means (orange line) and inter-quartile ranges between city types supports the claims made above.
![Fig2](https://user-images.githubusercontent.com/80861610/119691016-37d30180-be18-11eb-92af-abf4d23d95db.png)
![Fig3](https://user-images.githubusercontent.com/80861610/119691039-3d304c00-be18-11eb-973d-1ffe5665c666.png)
![Fig4](https://user-images.githubusercontent.com/80861610/119691054-402b3c80-be18-11eb-8f26-040196884b58.png)

This analysis also included the breakdown of total fare, total rides, and total drivers between city types. The following charts depict the expected results that the larger city types have a higher share of the total fare, total rides, and total drivers.
![Fig5](https://user-images.githubusercontent.com/80861610/119691677-c8a9dd00-be18-11eb-83b4-baf4c89b48aa.png)
![Fig6](https://user-images.githubusercontent.com/80861610/119691687-cb0c3700-be18-11eb-993b-6b9dd35561bb.png)
![Fig7](https://user-images.githubusercontent.com/80861610/119691710-ce072780-be18-11eb-8494-4d5061a07ad3.png)

Additionally, we see that the relation between total fares and city type was relatively constant throughout the first four months of 2019 (or more specifically, Jan. 1 - Apr. 29), such that in any given week, more fare was collected in urban cities than suburban ones and in suburban cities than rural ones. 

![Pyber_fare_summary](https://user-images.githubusercontent.com/80861610/119692455-6c938880-be19-11eb-9415-82cc935b2211.png)

Finally, the aggregate data on city types for Jan. 1, 2019 - May 8, 2019 show average fare per ride and per driver are less for more densely populated areas.
![image](https://user-images.githubusercontent.com/80861610/119693350-2ee32f80-be1a-11eb-933f-ab0b4a05b5af.png)

## Summary 
Three conclusions drawn from the analysis:
1. Although most of the companies total fare revenue (62.7%) comes from urban areas, less densely populated areas produce more revenue per ride and per driver. Thus, these areas should not be neglected in the company's strategy. Although the total possible revenue from these areas is less because of the simple fact that there are less people there, they gross more revenue per ride.
2. On the other hand, less densely populated areas tend to have higher fares than more densely populated ones. Two possible reasons for this are that the average length of trips may be longer, or the smaller supply (i.e., number of drivers) increases the average cost for consumers. If this latter hypothesis is right, average cost for customers could be reduced by recruiting more drivers in less densely populated cities.
3. A more focused study should be conducted to determine why several urban cities seem to have a relatively low number of drivers and low average fare to determine more precisely the relation between these two factors and what other factors affect this relation.



