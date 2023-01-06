# MechaCar_Statistical_Analysis
## Project Overview
* Perform multiple linear regression analyses to identify which variables in the dataset predict the mpg of MechaCar prototypes.
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, write a summary interpretation of the findings.

## Linear Regression to Predict MPG
The dataset for the 50 MechaCar prototype vehicles has 6 variables: (vehicle length, vehicle weight, spoiler angle, ground clearance, all-wheel-drive assignment, miles 
per gallon).



![Linear Regression to Predict MPG](https://user-images.githubusercontent.com/67697826/210939327-6660c308-79a9-4ed9-a31c-ca066b534629.png)
![Linear Regression to Predict MPG2](https://user-images.githubusercontent.com/67697826/210939338-d9a72de8-c0d2-4be7-8379-fe5765a4e696.png)

**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?** 
Vehicle length (2.60e-12 coefficient) and ground clearance (5.21e-08 coefficient) variables provide a non-random measure of variance to the MPG values within the dataset, which implies these variables would have a substantial impact to MPG. Vehicle weight, spoiler angle, and AWD each have coefficients > 0.05, which suggest these variables are much less likely to pose a considerable negative impact to the vehicles MPG. 

**Is the slope of the linear model considered to be zero? Why or why not?**
With the p-value being considerably smaller than the significance level of 0.05%, the slope of the linear model could not be zero.

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**
With an R-squared value of roughly 0.71, an accuracy of approximately 71% indicates the factors used to predict MPG in MechaCar’s prototypes would be quite effective.
