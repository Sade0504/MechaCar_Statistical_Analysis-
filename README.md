# MechaCar_Statistical_Analysis-
Statistical analysis of automobile performance with R

## Overview
AutosRUs has a new prototype named "the MechaCar". The company is having production issues with the manufacturing team's progress and has asked my data analytics team to review their production data. The main objective of this project is to:

* Identify which variables predict the MPG for vehicle prototypes;
* Collect summary Statistics on the PSI of the suspension coils;
* Determine if the manufacturing lots are statistically different from the mean population

## Linear Regression to Predict MPG
<img width="868" alt="Untitled" src="https://user-images.githubusercontent.com/100165760/177222818-58837438-fb17-4a5b-852c-900eeeaa7143.png">
"Vechicle Length" and "Ground Clearance" are the variables in our dataset that shows a non-random effect on the MPG of the MechCar. The image above depicts a linear regression model run on the variables mention above, against figures for MPG. 

## Summary Statistics on Suspension Coils
<img width="345" alt="Total Summary" src="https://user-images.githubusercontent.com/100165760/177223303-8cb49c81-d5ea-40e1-9489-29fdde17c452.png">
<img width="517" alt="Total Summary2" src="https://user-images.githubusercontent.com/100165760/177223314-2d555626-5872-4913-bacf-a69107c00289.png">
Although the Total Summary data above states that the overall variance is under 100 psi and meets specification, there is an issue with one of the lots. The image above shows that Lot3 is over the alloted threshold, at 170.28.
