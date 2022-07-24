# PyBer_Analysis
## Project Overview
Our task here for PyBer is to perform an exploratory anaylsis by utilizing visualizations to tell a compelling story about our data. Our analysis for this task is to use such charts to showcase the relationship between the type of city and the number of riders and drivers as well as the percentage of total fares, riders, and drivers by type of city. This will help PyBer improve access to ride-sharing services and determine affordability for underserved neighborhoods. 

## Resources
- Data Source: PyCitySchools.ipynb 
- Software: Python, Anaconda, Jupyter Notebook, Pandas, Matplotlib

# Results
## Summary DataFrame

![SummaryDataFrame](https://user-images.githubusercontent.com/107603065/180634095-3a2fb9cb-081c-4850-9cb2-c93be53cdff6.png)

According to the ride-sharing data above, as the city type changes to become more populated, the number of rides, drivers, and the total fares increase respectively. Given that the there are more people in Urban city types, the number of drives available as well as the number of rides given are quite higher compared to their suburban and rural counterparts. Interestingly enough, as the number of rides increase, because there are more drivers avaialable to increase the probability of more rides given, the average fare per ride and per driver decrease. This could simply be a result of increased supply, hence lowering the price per ride. This also results in an increase in total fare revenue that the city type brings as there is a directly proportional relationship between total fares and the number of rides and drivers, while it has an inversely proportionaly relationship with average fares. As rides and drivers become more scarce in smaller city types, the average price per ride would increase resulting in drivers having an increase average fare as a result.


## Multiple-Line Chart

![PyBer_Fare_Summary](https://user-images.githubusercontent.com/107603065/180634139-10c871d7-e68a-40d8-932e-e7fdaf88a681.png)

The **Total Fare by City Type** chart shows a steady trend across a period of 4 months, from January to April for all three city types. Towards the end of February however, there seems to be a decline in fare for all three city types, with the data showing more fluctuation within the Urban city type compared to the other two city types. Towards the beginning of April, we start to see a rise in fare, with the *Suburban* and *Urban* city types showing slightly similar upward trends, *Suburban* moreso than the latter, however, the *Rural* city type shows a steady decline after its short ride in the beginning of April. 


# Summary
Given the analysis and the data, the three recommendations that can be made are:
1. As seen in the data and from the analysis, profitability would come from more densely populated city types. Because of this, if PyBer's strategy is to improve the company's profitability, their focus should be investing within more urban city types compared to suburban and rural types. 
2. As we move away from more densely populated areas, access and affordability are main priorities to tackle. To improve affordability, PyBer could implement a different method of calculating fares or introduce carpooling methods that could split fares amongst riders. 
3. To improve accessibility, PyBer could introduce a call center strategy, in which riders could request rides via the call center in the abscense of smartphones. Futhermore, the carpooling method would allow for more riders to travel per ride compared to just one passenger per ride. 

Additionally, the data gathered here only spans over 4 months and there could be additional information to be gathered across an entire year in which could shed more light on how to improve access and affordability.
