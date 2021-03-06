# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The vehicle length, and vehicle ground clearance provided non-random amounts of variance to the mpg values in the dataset.

#### Is the slope of the linear model considered to be zero? Why or why not?
The p-value is 5.35e-11 which is significantly less than the assumed significance level of 0.05% . This provides us with enough information to reject our null hypothesis, meaning that slope of the linear model isnt zero.

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Yes this linear model predicts mpg of MechaCar prototyptes effectively. With a r-squared value of .7149 (71Z%) which indicates a signficant level of prediction.

![Screen Shot 2022-03-28 at 2 56 15 PM](https://user-images.githubusercontent.com/93875400/160467468-57ce2ff9-9db7-46ad-86c6-4960bf0f0d47.png)

## Summary Statistics on Suspension Coils

#### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
For the total summary the variance of the suspension coils is well below the limit at 62/29356. When you look at the variance of the suspension coils for each individual lot you see that lot1 and lot2 are will beneath the limit at .9795918 and 7.4693878 respectively. However, for lot3 the variance of the suspension coils is 170.2861224 which is well over the limit. 

![Screen Shot 2022-03-27 at 12 15 05 PM](https://user-images.githubusercontent.com/93875400/160290644-9ea6815b-4255-4b55-9779-fa40ed90c282.png)
![Screen Shot 2022-03-27 at 12 15 19 PM](https://user-images.githubusercontent.com/93875400/160290658-f699ac52-8a84-4b05-a79f-4da59f15d19f.png)

## T-Tests on Suspension Coils

### Summary of the t-test results across all manufacturing lots and for each lot.
![Screen Shot 2022-03-28 at 1 49 41 PM](https://user-images.githubusercontent.com/93875400/160457158-277405a8-732d-491a-8505-6a67104ea648.png)
![Screen Shot 2022-03-28 at 1 52 14 PM](https://user-images.githubusercontent.com/93875400/160457539-68e2d2d2-8fc9-4c9e-9842-5a854f2a5aa8.png)
![Screen Shot 2022-03-28 at 1 51 03 PM](https://user-images.githubusercontent.com/93875400/160457370-6e8e0d96-97b7-43ea-9c81-a15231b42462.png)
![Screen Shot 2022-03-28 at 1 51 25 PM](https://user-images.githubusercontent.com/93875400/160457424-08c84c99-79c9-4893-9f8d-c3d230867239.png)

## Study Design: MechaCar vs Competition
#### What metric or metrics are you going to test?
cost of vehicle.

##### What is the null hypothesis or alternative hypothesis?
null hypothesis: There is no difference between cost of vehicles of MechaCar and the competition.
alternative hypothesis: There is a significant diffference between the cost vehicles of MechaCar and the competition.

#### What statistical test would you use to test the hypothesis? And why?
I would use a two-sample t-test to determine if the mean cost is signicantly different between the know variables. 

#### What data is needed to run the statistical test?
I will the need the cost of the different types of vehicles for both MechaCar and their competition.
