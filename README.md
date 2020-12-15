# Foresee Your Activity: A Strava Machine Learning Project
Machine learning project using Strava data.  Our goal was to create data visualizations, analytics, and predictive modeling that could help athletes improve their training plan.  Fitness data was collected and analyzed from two participants.  A database was created using SQLite.  Data visualizations and analysis were created using Tableau.  Finally, classification and regression machine learning was conducted in Python and the Scikit-learn library.    

The project presentation can be found here: [Project Presentation](https://github.com/mocchicone/Strava-Fitness-Analysis/blob/master/Fitness%20Tracking%20Machine%20Learning.pdf)

The Tableau storyboard can be found here: [Strava Tableau Analysis](https://public.tableau.com/profile/john.bruner#!/vizhome/FitnessTrackingOverviewFinal/FitnessTrackingDataOverview)

## Tableu Visualizations:

We created a Location Analysis dashboard, that provides detailed data on each run as well as summary information on distance and temperature.

![Location Analysis](https://github.com/mocchicone/Strava-Fitness-Analysis/blob/master/machine_learning/Images/Location%20Analysis.PNG)

We also created a Performance Analysis dashboard.  In this example, we can see how much the user is running each month and how elevation change impacts his running speed.

![Performance Analysis](https://github.com/mocchicone/Strava-Fitness-Analysis/blob/master/machine_learning/Images/Performance_Analysis.PNG)

## Predictive Analytics Using Machine Learning (Classification and Regression):

*Classification Analysis*
* Can we use machine learning to accurately predict the type of workout based on factors such as heart rate, start time, and length of workout?

*Regression Analysis*
* Can running pace be predicted based on elevation, heart rate, temperature, and athlete count?

Various machine learning algorithms were utilized to understand how they would perform with the data set.  In the classification summary table below we can see that support vector analysis provided the most accurate results. 

![Classification](https://github.com/mocchicone/Strava-Fitness-Analysis/blob/master/machine_learning/Images/Classification_summary.PNG) 

## Contact Information
John Bruner: jmbruner37@gmail.com  
Andrew Cliffe: acliffe45@gmail.com  
Zhiyi Li: zhi465@ucsd.edu  
Michael Occhicone: mpocchicone@gmail.com


## File Locations:
* Presentation: fitness trakcing machine learning.pdf
* Machine learning classification: -> Machine Learning -> Classification
* Machine learning regression: -> Machine Learning -> Regression
* SQL Database: -> database_zhiyi -> database_creation.ipynb + fitness_database.sqlite 
* Tableau: Fitness Tracking Overview Final.twbx
* Web: index.html



