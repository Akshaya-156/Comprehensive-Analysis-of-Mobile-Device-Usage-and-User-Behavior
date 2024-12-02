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
### EXPLORATORY DATA ANALYSIS: <br>
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
 ### DATA VISUALIZATION : <br>
#### Insights from Each Plot <br>

#### App Usage Time (min/day):<br>
#### 1.Peaks at around 100–200 minutes, indicating most users spend about 1.5 to 3 hours daily on apps. <br>
#### 2.Distribution has a long tail, suggesting some users spend significantly more time. <br>

#### Screen On Time (hours/day):<br>
#### 1.Most users have 2–4 hours of screen-on time per day. <br>
#### 2.Declines after 4 hours, with fewer users spending 8–12 hours on their devices. <br>

#### Battery Drain (mAh/day): <br>
#### 1.A significant portion of users experience 500–1000 mAh battery drain per day. <br>
#### 2.The distribution is slightly right-skewed, implying some users have higher battery drain, likely due to heavy usage. <br>

#### Data Usage (MB/day): <br>
#### 1.Peaks at 0–500 MB/day, suggesting most users are light to moderate data consumers. <br>
#### 2.Some users consume upwards of 2000 MB/day. <br>

#### Number of Apps Installed: <br>
#### 1.Distribution is fairly uniform, with a slight peak at around 20–40 apps. <br>
#### 2.Indicates diverse user behaviors regarding app installations. <br>

#### Age: <br>
#### 1.Relatively uniform distribution across all age groups. <br>
#### 2.Minor peaks in the 20s and 50s suggest higher representation of younger and middle-aged users. <br>

 ![image](https://github.com/user-attachments/assets/98c17290-3e23-46d7-90d3-100eee880cae) <br>

 #### Observations from the Heatmap: <br>
 
#### High Correlations: <br>

#### 1.App Usage Time vs. Screen On Time (0.95): <br>
 Strong positive correlation indicates that users who spend more time on apps also have higher overall screen-on time. <br>
#### Insight: These two metrics are tightly linked, so app usage heavily influences total screen-on time. <br>

#### 2.App Usage Time vs. Battery Drain (0.96): <br>
 App usage has a strong impact on battery consumption. <br>
#### Insight: Heavy app users likely face battery drain issues, and optimizations can focus on app resource consumption. <br>

#### 3.App Usage Time vs. Data Usage (0.94): <br>
 Positive correlation suggests that increased app usage leads to more data consumption. <br>
#### Insight: Heavy app users also consume more mobile data. This is useful for telecom companies and app developers in providing data-usage alerts or saving features.  <br>

#### 4.Battery Drain vs. User Behavior Class (0.98): <br>
 A very high correlation suggests that user behavior class is a strong predictor of battery consumption. <br>
#### Insight: Behavior classes (e.g., high usage categories) can directly help in modeling battery drain. <br>

#### 5.Screen On Time vs. Battery Drain (0.95): <br>
 Longer screen-on time contributes significantly to higher battery usage. <br>
#### Insight: Power-saving features can focus on screen efficiency, such as dimming brightness or reducing screen-on time for idle periods. <br> 

#### Low/No Correlation:  <br>

#### 1.Age vs. App Usage Time (0.00):
  No correlation suggests that app usage time is independent of age. <br>
#### Insight: Usage patterns are not influenced by the age of the user. Marketing and app personalization should focus on behavior rather than demographics. <br>

#### 2.Age vs. Data Usage (0.00): <br>
#### Similarly, no relationship exists between age and data usage, highlighting behavior over demographics as the primary factor.  <br>

#### Moderate Correlations: <br> 

#### 1.Number of Apps Installed vs. App Usage Time (0.96):  <br>
 A positive correlation implies that users with more apps installed tend to use their devices more actively.  <br>
#### Insight: Encouraging users to install more apps could lead to greater device engagement. <br>

 ![image](https://github.com/user-attachments/assets/74fc817a-855f-47ff-a01c-5380be2d790c)




