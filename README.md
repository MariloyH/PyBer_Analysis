# PyBer_Analysis

BootCamp Week 5

# Overview
Our Client, PyBer, is a Ride-sharing App Company asked us to perform an analysis of its operations, so that they can make decisions that lead to an improvement in its services. We must create a summary of the ride-sharing data by city type and we will present it along with graphs. We will deliver a  written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# Results
## Merging the 2 databases to get the required data
From the available data of PyBer,  citi_data.csv & the ride_data.csv, we created a Data Frame with the information we will need for the purpose of this proyect. Using the *groupby dataframe function* to get the total number of trips made, the total number of drivers and the rates per driver and per trip, this  for each type of trips the company makes: Urban, Suburban and Rural. 


<img width="621" alt="Totals per city" src="https://user-images.githubusercontent.com/102195803/167002464-f8ed080e-51e6-4b9b-9f68-d7cbce0fe203.png">

## Refinig the data
In order to plot the results, we performed several operations in the previous data frame to perform the analysis. 

<img width="601" alt="FarebyDate_DF" src="https://user-images.githubusercontent.com/102195803/167001624-6486686a-b8c7-4c8b-9813-0dc7ccc30c89.png">

We were looking the total fares and number of rides per city, We transform the final Data Frame into a Pivot Table resample the data form January to May, 2019.

<img width="548" alt="Copia de Resampled_data" src="https://user-images.githubusercontent.com/102195803/166987720-4b41825e-4bc8-416b-8127-7d3fdfe6e5b9.png">

## Final Results
Finally, we plot the results to observe how fares have changed over time depending on city type.

<img width="279" alt="Final DataFrame" src="https://user-images.githubusercontent.com/102195803/166987893-1da23ff9-97ee-4eca-938a-967be9ab3b10.png">


![image](https://user-images.githubusercontent.com/102195803/167016456-3372fcdc-3389-4b79-93d4-c4299ab9ab0b.png)

## Describe the differences in ride-sharing data among the different city types.

From the first image, we could observe that the Urban rides are the most profitable of the company during this period. Althought in its majority they are no so expensive, (their average fare was of $24.53 USD), there were more, in a reaseon of 13 city rides per one rural ride.
They have also more drivers, which seems logiucal,  because because the cities have more people and more traffic, and the people is changing to Ride Apps transportation.  On the other hand, rural rides are less frequent, hence it has less  drivers, but, due the distances, there are more expensive than city rides, as the fare per driver shows. Its higher, but its not profiterable due its less frequency,  and here it is an opportunity to explore, because maybe ther are not enough rural drivers. Suburban rides are the average as much as fares than in frequency ant its respresent an important part of the Company´s revenues.  


# Summary: 
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

From this results, we have 3 recommendations:
  1) Motivate an increase of Urban rides, due they are the most important part of the bussines revenues, but its not consistent with the number of asigned drivers. 
  2) Establish a Fare goal for Suburban cities, paying atention to its number of drivers, because  its a city type with a lot of growth         potential. 
  3) Expand the scope to rural cities that are not considered yet, maybe more advertising or adding promotions, because maybe the competition here is between bus transportation, so maybe a minor fare could motivate people to use Ride Apps.   

