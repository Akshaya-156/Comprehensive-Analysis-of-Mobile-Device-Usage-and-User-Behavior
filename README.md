# Comprehensive-Analysis-of-Mobile-Device-Usage-and-User-Behavior

### Problem Statement:  <br>
#### This project analyzes mobile device usage and user behavior to understand: <br>
#### 1.How users interact with mobile devices throughout the day.  <br>
#### 2.The relationship between app categories and user engagement.  <br>
#### 3.Insights into how factors like age, app type, and screen time impact overall behavior.  <br>

### Objective:  <br>
#### Provide actionable recommendations for improving user experience, optimizing app performance, and encouraging healthy mobile usage habits. 
#### The goal of this analysis is to:

#### 1.Understand the distribution of key metrics such as app usage time, screen on time, battery drain, data usage, number of apps installed, and age across the users.<br>
#### 2.Explore correlations between different numerical features to identify any relationships between user behavior metrics.<br>
#### 3.Summmarize statistics to identify patterns, outliers, and central tendencies in the data.<br>
####  The insights derived from this analysis could help improve user experience, optimize mobile device performance, and drive product decisions based on user behavior and preferences.

### Dataset Overview: <br>
The dataset contains data about user behavior and smartphone usage patterns. Here is a breakdown of the dataset's columns and their descriptions: <br>

#### 1.User ID: A unique identifier for each user (integer). <br>
#### 2.Device Model: The smartphone model used by the user (string). <br>
#### 3.Operating System: The operating system of the smartphone (either Android or iOS). <br>
#### 4.App Usage Time (min/day): The average number of minutes per day the user spends on apps (integer). <br>
#### 5.Screen On Time (hours/day): The average number of hours per day the user's screen is on (float). <br>
#### 6.Battery Drain (mAh/day): The average battery consumption per day in milliampere-hours (mAh) (integer).<br>
#### 7.Number of Apps Installed: The total number of apps installed on the user's device (integer).
#### 8.Data Usage (MB/day): The average data consumption per day in megabytes (MB) (integer). <br>
#### 9.Age: The age of the user (integer). <br>
#### 10.Gender: The gender of the user (string, typically "Male" or "Female"). <br>
#### 11.User Behavior Class: A categorical class representing user behavior (integer values from 1 to 5). <br>
Class 1: Low engagement or usage.<br>
Class 2-3: Moderate engagement or average usage patterns.<br>
Class 4: High engagement, possibly power users or frequent app users.<br>
Class 5: Very high engagement, possibly including users who consume a lot of data, have many apps installed, and spend a lot of time on their devices. <br>

### STATISTICAL INSIGHTS : <br>
#### It is a cleaned dataset <br>
#### 1.App Usage Time and Screen On Time have a wide range, with some users having significantly higher usage than others. <br>
 1.1.Range: app usage -The minimum is 30 minutes, and the maximum is 598 minutes.<br>
 1.2.Range : screen time -The minimum is 1 hour, and the maximum is 12 hours.
#### 2.Battery Drain also shows a wide spread, with users consuming a large range of battery levels. <br>
 2.1.Range: The minimum is 302 mAh, and the maximum is 2993 mAh..<br>
#### 3.The Age of users varies between 18 and 59, with a mean age of 38, indicating a fairly broad age range. <br>
  3.1.Range: The minimum age is 18, and the maximum age is 59.<br>
#### 4.The Number of Apps Installed and Data Usage values also show considerable variability across users. <br>
  4.1.Range: The minimum is 10 apps, and the maximum is 99 apps.
#### 5.The User Behavior Class provides a categorical classification that likely represents different patterns of behavior, though its exact meaning would require further exploration. <br>
 5.1.Range: The classes range from 1 to 5.
 


