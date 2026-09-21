# Stats-for-Data-Science---Wildfires

## Overview
Wildfires in California have become increasingly destructive, burning millions of acres and threatening communities, ecosystems, and air quality. My team and I found interest in this topic as fires are something that continues to impact California and we are all currently residing in this state. 

## Business Problem
Do factors such as temperature, precipitation, wind speed, and seasonal patterns play a role in how frequent and severe wildfires occur? 


## About Data Set 
Dataset is collected from fire incident reports from CAL Fire 
   Dataset includes:
    - Incident acres burned
    - Incident Date
    - Precipitation
    - Max Temp
    - Min Temp
    - Average Wind Speed

Weather Dataset was also used
The data is collected from meteorological data from NOAA Climate Data Online with fire incident data from CAL FIRE

Both Wildfire Dataset and Weather Data set were merged together and cleaned to be able to do visualizations and form conclusions 
SPSS was used to conduct descriptive analysis, correlation analysis, and regression analysis


## Analysis 


### Descriptive Statistics
### Fire size (acres):

- Mean ~ 4,602 acres,
- Standard deviation very large (42,893), with a maximum of 1,032,648 acres → indicates extremely skewed distribution, with a few     megafires inflating the average.
- Temperature (MAX_TEMP): Range 59–102°F, mean 74.4°F → most fires occur in warm/hot weather.
- Precipitation (PRECIPITATION): Mean only 0.003 inches → essentially zero, showing that most fires occur under dry conditions.
- Wind speed (AVG_WIND)

### Correlation Analysis
- Fire size vs. temperature → weak positive correlation.
- Fire size vs. wind speed → weak positive correlation.
- Fire size vs. precipitation → almost no correlation (fires mostly occur without rainfall)
  
### Regression Analysis

### Temperature vs. Log fire size (Figure below):
   Using regression analysis, trend shows higher temperature associated with larger fires, but with high scatter → temperature   matters but is not the sole determinant.
![Temperature vs. Log Fire Size](images/regression-analysis.png)


## Results
- Summer has the highest frequency in fires.
- Weather (temperature and wind speed) influence wildfire size, but correlations are generally weak. 
- Temperature and wind speeds are significant positive predictors of wildfire size, but overall model explanatory power remains low.



## Conclusion + Recommendation 
While temperature and wind speed play a role, they are not the only drivers of California wildfires; other factors such as vegetation, topography, and human activity are also important.


Note:
- This project was a group effort by Luisa Garate, Naomi Hossain, Vivi ( Xinyi) He,  Wayne (Weinou) Jin, & Tysean Haigood
