# PyBer_Analysis

BootCamp  Challenge Week 5: Pyber Analysis

# Overview
Our Client, PyBer, is a Ride-sharing App Company asked us to perform an analysis of its operations, so that they can make decisions that lead to an improvement in its services. We must create a summary of the ride-sharing data by city type and we will present it along with graphs. We will deliver a  written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# Results
## Merging the 2 databases to get the required data
From the available data of PyBer,  citi_data.csv & the ride_data.csv, we created a Data Frame with the information we will need for the purpose of this proyect. We use the *groupby dataframe function* to get the total number of rides, the total number of drivers and the fares per driver and per ride, and we sort for the city type  the company has: Urban, Suburban and Rural. 


<img width="621" alt="Totals per city" src="https://user-images.githubusercontent.com/102195803/167002464-f8ed080e-51e6-4b9b-9f68-d7cbce0fe203.png">

## Refinig the data
In order to plot the results, we performed several operations in the previous data frame to perform the analysis and selecte a period of time as a sample for this analysis. 

<img width="601" alt="FarebyDate_DF" src="https://user-images.githubusercontent.com/102195803/167001624-6486686a-b8c7-4c8b-9813-0dc7ccc30c89.png">

So we were looking the total fares and number of rides per city, it was necessary transform this Data Frame: first, we select the period of time and transform the resulting DataFrame  into a Pivot Table and  Resample the data in Weeks.

**Pivot Table**
<img width="321" alt="PivotTable" src="https://user-images.githubusercontent.com/102195803/167021458-f5bed148-41c9-4703-b871-20ea13509b81.png">

**Resample data**
<img width="548" alt="Copia de Resampled_data" src="https://user-images.githubusercontent.com/102195803/166987720-4b41825e-4bc8-416b-8127-7d3fdfe6e5b9.png">

## Final Results
Finally, we plot the results to observe how fares changed over time depending on city type.

**Resulting Data Frame**
<img width="279" alt="Final DataFrame" src="https://user-images.githubusercontent.com/102195803/166987893-1da23ff9-97ee-4eca-938a-967be9ab3b10.png">

**Plotting results**

![image](https://user-images.githubusercontent.com/102195803/167016456-3372fcdc-3389-4b79-93d4-c4299ab9ab0b.png)

## Describe the differences in ride-sharing data among the different city types.
In the first table, we showed the numbers of the company during a period of time, sorted by city type: the total rides, total drivers, total fares, average fare per ride and driver. 
From this, we could observe that the Urban rides are the most profitable ride of the company during this period of time due its quantity. Urban Rides are not so expensive, as we can compare in the Average Fare per Ride Column. ($24.53 USD per Urban Ride in comparison with the $34.62 of the  Rural Ride).  Otherwise, althought the Rural Average Fare per Ride is the highest of the three types, its low frequency makes a huge diference among the Total Fares per City type.   
We can see that Urban City have also more drivers, which seems logical,  because because the cities have more people and more traffic, and the people is prefering Ride Apps transportation than bus or taxi. In Rural Cities, its low frequency it is an opportunity to explore, because maybe ther are not enough rural drivers or maybe the fare is high for average consumer.  Suburban rides are in the middle as much as fares,   in frequency, but they  respresent an important part of the Company´s revenues, so it is a sector that should be promoted in order to grow PyBer´s income. 

# Summary: 
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

From this results, we have 3 recommendations:
  1) Motivate an increase of Urban rides, due they are the most important part of the bussines revenues, but its not consistent with the number of asigned drivers. 
  2) Establish a Fare goal for Suburban cities, paying atention to its number of drivers, because  its a city type with a lot of growth         potential. 
  3) Expand the scope to rural cities that are not considered yet, maybe more advertising or adding promotions, because maybe the competition here is between bus transportation, so maybe a minor fare could motivate people to use Ride Apps.   

