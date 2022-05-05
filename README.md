# PyBer_Analysis
BootCamp Week 5
Use your repository README file to write your analysis of how to address any disparities in the ride-sharing data among the city types.
# Overview
PyBer is a transportation by Aplication Company. We must create a summary of the ride-sharing data by city type and we will present this in a  multiple-line graph that shows the total weekly fares for each city type. We will deliver a  written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# Results
## Merging the 2 databases to get the required data
From the data of  the citi_data.csv & the ride_data.csv we created a new Data Frame with the information we need for the purpose of this proyect, by using the *groupby dataframe function* to get the total number of trips made, the total number of drivers and the rates per driver and per trip, this  for each type of trips the company makes: Urban, Suburban and Rural. 

![image](https://user-images.githubusercontent.com/102195803/166848804-937c262e-54d2-4f3c-9d28-fd85fa4b8489.png)

## Refinig the data
In order to get the necessary data, we perform several operations in the previous data frame to get the total fares per city type.   to perform the analysis. Later, we transform the final Data Frame and resample the data form January to May, 2019.
![image](https://user-images.githubusercontent.com/102195803/166849666-4ce12e10-23be-4134-827d-d04c73a321c6.png)
Finally, we plot the results to observe how fares have changed over time depending on city type.


describe the differences in ride-sharing data among the different city types.
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
