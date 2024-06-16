# Exploratory Data Analysis on Weather using Python
![IgorZh/Shutterstock](weather_jpg.jpg)

## INTRODUCTION: 
The Weather Dataset is a time-series dataset with per hour information about the weather condition at a particular location. it records Temperature, Dew point temperature, Relative Humidity, Wind speed, visibility, pressure and conditions. 
This project is an Exploratory Data Analysis conducted on the weather dataset, which aims at detecting patterns and relationships, generating questions and hypotheses and informing subsequent analysis.

## CONCEPT APPLIED: 
*Libraries* used include: pandas, numpy, matplotlib.pyplot, seaborn,statistics and calendar.


## DATA SOURCING:
The data set can be found [here]( https://datasciencelovers.graphy.com/products/Dataset--Project-1---Weather-Data-Analysis-64d48ec74065076bdfbcc4db?dgps_u=l&dgps_s=ucpd&dgps_t=cp_u&dgps_u_st=p&dgps_uid=666ad57c832a2903ef630ebb)

The dataset contains 8784 rows and 8 columns


## PROBLEM STATEMENTs:
1. Get all unique values of the 'weather_condition' column
2. Find all the unique windspeed value
3. Find the number of times when the 'Weather is exactly clear'
4. Find all instances when the 'Wind Speed was exactly 7 km/hr'
5. Find the minimum date and the maximum date recorded
6. Explore the correlation, relationships between the numerical columns¶
7. Visualise the relationship between Relative Humidity in percent and Visibility in km
8. Visualise the relationship between Temperature and Dew Point Temperature in Celsius
9. Get the seasonal change in Visibility
10. Visualize the frequency of each weather condition
11. Visualising the frequency of weather conditions by month
12. Find all instances when snow was recorded
13. Find mean value of each column for each 'Weather category'
14. Get all instances where weather category is precipitation(Rain) and Relative humidity is greater than 50 and Visibility is less than 40
15. Visualize the seasonal Changes in temperature


## CONCLUSION:
From our analysis we were able to understand our datasets better, identify patterns in regards to month and  to  detect several relationships in our data. For further analysis we can collect data from other years, and we can also perform transformations on the 'Pressure_kPa' column to better understand it's relationship with the rest of the columns.