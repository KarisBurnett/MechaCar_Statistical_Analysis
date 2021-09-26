# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
![Linear Regression](https://user-images.githubusercontent.com/85076259/134822323-afcad568-3037-42d8-b452-83caa8e18803.PNG)

The screenshot above shows the results of producing a linear regression model to predict MPG from the MechaCar_mpg dataset using the variables: vehicle length, vehicle weight, spoiler angle, ground clearance,AWD and mpg. Of these variables, vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset, as shown by their low p-values. The slope of the linear model is not considered to be zero because the estimates for all coefficients are not zero. This model predicts the mpg of MechaCar protoypes effectively because the Adjusted R-squared reflects that 68.25% (0.6825) of the variation within mpg is explained by the coefficients.

## Summary Statistics on Suspension Coils
![Suspension Coils Summary](https://user-images.githubusercontent.com/85076259/134823205-fb530b22-ffd3-4b55-8526-c58cf0fdc339.PNG)

Summary statistics, which include: the mean, median, variance, and standard deviation of the PSI, were pulled and are shown above for the suspension coils and for the manufacturing lots. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch (PSI). Based on the variance of the suspension coils in the total summary, the suspension coils overall meet the MechaCar design specifications. However, the lot summary shows that although Lots 1 and 2 meet the design specifications and have variances under 100 PSI, Lot 3 does not meet the design specifications as its variance is much over the 100 PSI limit.

## T_Tests on Suspension Coils
![T-Tests](https://user-images.githubusercontent.com/85076259/134823672-ff237cf3-3357-48b6-a3cd-db84202e4a19.PNG)

The results of the t-test to determine if the PSI across all manufacturing lots are statistically different from the population mean of 1,500 PSI, shows that at a 95% confidence level, the two means are not statistically different. The p-value of 0.06 is higher than the critical value of 0.05 so the null hypothesis can be accepted since there is no difference between the means of the PSI for the population and overall manufactung lot sample.  The means within the 95% confidence range are between 1497.5 and 1500 PSI. 

The results of the t-test to test if the PSI mean for Lot1 is statistically different from the population mean of 1,500 PSI show that at a 95% confidence level the two means are not statistically different. The p-value of 1 shows that the mean for Lot1 is exactly the same as the population mean of 1500 PSI. 

The results of the t-test to test if the PSI mean for Lot2 is statistically different from the population mean of 1,500PSI show that at a 95% confidence level the two means are not statistically different. Because the p-value of 0.61 is higher than the critical value of 0.05 the null hypothesis can be accepted since there is no difference between the means of the PSI for the population and Lot2. The means within the 95% confidence range are between 1499.42 and 1500.97 PSI.

The results of the t-test to test if the PSI mean for Lot3 is statistically different from the population mean of 1,500 PSI show that at a 95% confidence level the two means are statistically different. Because the p-value of 0.04 is lower than the critical value of 0.05 the null hypothesis should be rejected since there is a difference between the means of the PSI for the population and Lot3 and the true mean is not equal to 1500. The means within the 95% confidence range are between 1492.43 and 1499.85 PSI.

## Study Design: MechaCar vs. Competition

Consumers are interested in several key metrics such as: budget, fuel eficiency, safety ratings, size, and horsepower (gotta climb the mountains). As a consumer that recently began looking for a new car, I am assuming that MechaCar is intended as a family vehicle. I would choose: fuel efficiency and safety as the top two factors in determining a preference.

First, we need to gather data on the MechaCar and its competitors in the following categories:Fuel efficiency and Safety Rating. I would use a two-sample t-test to determine if there is a statistical difference between the two.

  H1 = There is no statistical difference between the MechaCar and it's competitor.

  H2 = There is a statistical difference between the MechaCar and it's competitor.

I would also choose the standard p = 0.05 as my tolerance level to accept or reject the null hypothesis.
