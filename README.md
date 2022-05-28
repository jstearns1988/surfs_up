# surfs_up
Analyzing Oahu weather data with Jupyter Notebook, SQLite, and Flask

## Overview
To assist W. Avy in making the decision to open a surf shop, an analysis of temperature trends in Oahu for the months of June and December was performed. The outcome will help determine if the surf and ice cream shop business is sustainable year-round.

## Results
The temperature trends for the months of June and December span the years 2010 to 2017. As seen in the dataframes below, the differences in temperatures between June and December are not drastically different.

### June Temperature DataFrame
![June Temperature DataFrame](https://github.com/jstearns1988/surfs_up/blob/main/Analysis%20Resources/June%20temps%20screenshot.png)

### December Temperature DataFrame
![Dec Temperature DataFrame](https://github.com/jstearns1988/surfs_up/blob/main/Analysis%20Resources/Dec%20temps%20screenshot.png)

### Three key differences in the weather between June and December
  - The average Oahu temperature for the month of June is approximately 75 degrees, whereas, the average temperature for December is 71 degrees. This is just a four degree difference.
  - The maximum temperature for June was 85 degrees, and the maximum temperature for December is 83 degrees. This is a two degree difference.
  - The minimum temperature for June was 64 degrees, while the minimum temperature for December is 56 degrees. At an 8 degree difference, the minimum temperature is the largest contrast in temperature data.

#### Based on the temperature data observed for the months of June and December alone, it is determined a surf shop that serves ice cream can be successful if opened in Oahu. The temperature differences only vary between two and 8 degrees. The lowest temperature recorded in December is still way above freezing and suitable for an ice cream fanatic to enjoy a treat.

## Summary

### Spring and Autumn Analysis

The temperature data shows there is not a dramatic change in temperatures in the months of December and June. To present even more decision making data to W. Avy, I wanted to show temperature data for months in the remaining seasons not previously analyzed: Spring and Autumn. I duplicated the queries I performed earlier on the months of March and October, calculated the summary statistics, and printed dataframes.
[View code here](https://github.com/jstearns1988/surfs_up/blob/main/Analysis%20Resources/March_Oct_query.ipynb)

### March Temperature DataFrame
![March Temperature DataFrame](https://github.com/jstearns1988/surfs_up/blob/main/Analysis%20Resources/March%20temps%20screenshot.png)

### October Temperature DataFrame
![Oct Temperature DataFrame](https://github.com/jstearns1988/surfs_up/blob/main/Analysis%20Resources/Oct%20temps%20screenshot.png)

  - The average March temperature is 70 degrees, while the average October temperature is 75 degrees. March and December have similar average temperatures with December's being one degree higher than March. June and October have the same average temperature.
   - The maximum temperature for March is 82 degrees, once again one degree lower than the December results. The maximum temperature for October is 86, one degree warmer than the maximum temperature in June.
  - The minimum temperature for March is 56 degrees matching that of December. The minimum temp for October is 64 degrees, the same as June.
 
 #### From these additional queries for March and December, we can determine Spring and Autumn temperatures do not differ much from the results for June and December. Based on temperature alone, each season has summary statistics with no dramatic differences.
 

### Additional Precipitation Analysis

I also wanted to look at weather beyond just temperature. Precipitation can also play a factor in the interest in surfing and ice cream. To be thorough, I decided to present my client with June and December precipitation data.
[View code here](https://github.com/jstearns1988/surfs_up/blob/main/Analysis%20Resources/Precipitation_query.ipynb)

### June Precipitation DataFrame
![June prcp DataFrame](https://github.com/jstearns1988/surfs_up/blob/main/Analysis%20Resources/June%20prcp%20screenshot.png)

### December Precipitation DataFrame
![December prcp DataFrame](https://github.com/jstearns1988/surfs_up/blob/main/Analysis%20Resources/Dec%20prcp%20screenshot.png)
  - The average precipitation in June is .14 inches, while the average precipitation in December is .22 inches. Rainfall is light for both months with December coming in slightly higher.
  - The maximum precipitation in June is 4.43 inches, and the maximum for December is 6.42 inches. If you look at how low the average rainfalls measure out, these maximum results appear to be outliers and not a common occurance. 
  - The minimum precipitation for both June and December is 0. This shows that not every day will have rain.
 
 #### After performing an analysis on the precipitation for June and December, I still stand by my conclusion that W. Avy should be confident in opening a surf and ice cream shop based on the observed weather data.
