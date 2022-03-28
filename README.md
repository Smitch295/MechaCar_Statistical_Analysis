# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The vehicle length, and vehicle ground clearance provided non-random amounts of variance to the mpg values in the dataset.

### Is the slope of the linear model considered to be zero? Why or why not?
The p-value is 5.35e-11 which is significantly less than the assumed significance level of 0.05% . This provides us with enough information to reject our null hypothesis, meaning that slope of the linear model isnt zero.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?


## Summary Statistics on Suspension Coils

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
For the total summary the variance of the suspension coils is well below the limit at 62/29356. When you look at the variance of the suspension coils for each individual lot you see that lot1 and lot2 are will beneath the limit at .9795918 and 7.4693878 respectively. However, for lot3 the variance of the suspension coils is 170.2861224 which is well over the limit. 

![Screen Shot 2022-03-27 at 12 15 05 PM](https://user-images.githubusercontent.com/93875400/160290644-9ea6815b-4255-4b55-9779-fa40ed90c282.png)
![Screen Shot 2022-03-27 at 12 15 19 PM](https://user-images.githubusercontent.com/93875400/160290658-f699ac52-8a84-4b05-a79f-4da59f15d19f.png)

## T-Tests on Suspension Coils
### An RScript is written for t-test that compares all manufacturing lots against mean PSI of the population (5 pt)
### An RScript is written for three t-tests that compare each manufacturing lot against mean PSI of the population (10 pt)
### There is a summary of the t-test results across all manufacturing lots and for each lot (5 pt)
