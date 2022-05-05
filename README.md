# PyBer_Analysis

BootCamp Week 5

# Overview
Our Client, PyBer, is a Ride-sharing App Company asked us to perform an analysis of its operations, so that they can make decisions that lead to an improvement in its services. We must create a summary of the ride-sharing data by city type and we will present it along with graphs. We will deliver a  written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# Results
## Merging the 2 databases to get the required data
From the available data of PyBer,  citi_data.csv & the ride_data.csv we created a Data Frame with the information we will need for the purpose of this proyect, by using the *groupby dataframe function* to get the total number of trips made, the total number of drivers and the rates per driver and per trip, this  for each type of trips the company makes: Urban, Suburban and Rural. 

![image](https://user-images.githubusercontent.com/102195803/166848804-937c262e-54d2-4f3c-9d28-fd85fa4b8489.png)

<img width="500" alt="THS 9th_replacedscores" src="https://user-images.githubusercontent.com/102195803/166848804-937c262e-54d2-4f3c-9d28-fd85fa4b8489.png">

## Refinig the data
In order to get the necessary data, we perform several operations in the previous data frame to perform the analysis. We were looking the total fares per city, number of rides, number of driver per city, We transform the final Data Frame and resample the data form January to May, 2019.
<img width="500" alt="Fares_by_type_and_date" src="https://user-images.githubusercontent.com/102195803/166987748-c50c5cba-99f9-4d28-9a5a-c9cb741993e5.png">

![image](https://user-images.githubusercontent.com/102195803/166849666-4ce12e10-23be-4134-827d-d04c73a321c6.png)

<img width="548" alt="Copia de Resampled_data" src="https://user-images.githubusercontent.com/102195803/166987720-4b41825e-4bc8-416b-8127-7d3fdfe6e5b9.png">

Finally, we plot the results to observe how fares have changed over time depending on city type.
<img width="500" alt="THS 9th_replacedscores" src="https://user-images.githubusercontent.com/102195803/165583518-e8c2e7a7-3d02-4dfe-8225-b7fc7a5f495f.png">

<img width="279" alt="Final DataFrame" src="https://user-images.githubusercontent.com/102195803/166987893-1da23ff9-97ee-4eca-938a-967be9ab3b10.png">


PyBer_fare_summary.png

## Describe the differences in ride-sharing data among the different city types.
We can observe that the Urban rides were more profitable along the first 4 months if the year, in comparison with tne Rural rides. 
At first sight we can think that rural rides are not so good because they are nor profitables, if we saw the statisticis we can observe that rural rides are not so frequent as the Urban. 

Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
Deliverable 3 Requirements
Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections. (2 pt)
Each section has a heading and subheading. (2 pt)
Links to images are working and displayed correctly. (2 pt)
Analysis (14 points)
The written analysis has the following:



Overview of the analysis:

The purpose of the new analysis is well defined. (3 pt)
Results:

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)
Summary:

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
