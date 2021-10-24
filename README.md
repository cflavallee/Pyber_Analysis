# Pyber Analysis

## Overview
The purpose of this analysis is to examine PyBer data from a specific time frame as it relates to city type: Urban, Suburban, and Rural.  Various categories are highlighted and a line graph of weekly fares by city type was created.  The analysis of PyBer data in this way can assist the company in its decision making process for operations within these three city types. 

## Results
Below are the results from creating DataFrames based on a nubmer of categories. The individiual numbers by category are given as well as a summary table.  As one might expect, Urban areas had higher total numbers, however, Rural areas had the highest fare per ride average, as well as average fare per driver. This could be due to the greater distance between destinations in rural areas. Additionally, a category for the number of rides per driver was added to see how productive the drivers were in each type of city.

### Total Ride Count
- Urban: 1625
- Suburban: 625
- Rural: 125

### Total Driver Count
- Urban: 2405
- Suburban: 490
- Rural: 78

### Total Fare Count
- Urban: $39,854.38
- Suburban: $19,356.33
- Rural: $4,327.93

### Average Fares per Ride
- Rural: $34.62
- Suburban: $30.97
- Urban: $24.53

### Average Fares by Driver
- Rural: $55.49
- Suburban: $39.50
- Urban: $16.57

### Ride Count per Driver
- Urban:  0.67 rides per driver
- Suburban: 1.27 rides per driver
- Rural:  1.60 rides per driver

### Summary DataFrame
![PyBer Summary](https://github.com/cflavallee/Pyber_Analysis/blob/main/analysis/Summary%20DataFrame.PNG)


### Total Fares by Week
![PyBer Summary](https://github.com/cflavallee/Pyber_Analysis/blob/main/analysis/TotalFare.png)


## Analysis Summary 
Based on the parsed data, there are various disparities that became apparent.  Further research would need to be done in order to confirm the reasons behind the numbers disparities, as factors other than city type could affect the numbers.  However, this analysis gives a starting point for possible changes.  Below are three reccomendations for the PyBer decision makers in order to increase productivity.  

- Decrease the number of Urban drivers.  There were more drivers than total rides, which means that some drivers did not give any rides during the given time frame.  It is not clear from the raw data why this was the case, but it is clear that there are drivers in Urban areas that are not needed. 

- Increase the number of Rural drivers.  While increasing the number of Rural drivers dramatically may not be beneficial, there should be a threshold higher than the current number of Rural drivers that would increase profit.  Given the presumed shorter ride length in Urban and Suburban areas, one would assume the drivers would average more rides.  However, the Rural drivers averaged more rides.  Rural areas also averaged a higher average fare per ride. 

- Adjust the pricing structure to maximize profit.  There may be an opportunity to increase prices in Urban areas as well as adjust pricing in the other two types.  A look at the average ride distance/length would be beneficial to see how it affects price and the number of rides per driver.  The main question to ask when it comes to pricing is: how should convenience, ride distance/length, and the date and time of the ride be weighted?