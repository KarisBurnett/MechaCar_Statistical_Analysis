# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
![Linear Regression](https://user-images.githubusercontent.com/85076259/134822323-afcad568-3037-42d8-b452-83caa8e18803.PNG)

The screenshot above shows the results of producing a linear regression model to predict MPG from the MechaCar_mpg dataset using the variables: vehicle length, vehicle weight, spoiler angle, ground clearance,AWD and mpg. Of these variables, vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset, as shown by their low p-values. The slope of the linear model is not considered to be zero because the estimates for all coefficients are not zero. This model predicts the mpg of MechaCar protoypes effectively because the Adjusted R-squared reflects that 68.25% (0.6825) of the variation within mpg is explained by the coefficients.

## Summary Statistics on Suspension Coils
![Suspension Coils Summary](https://user-images.githubusercontent.com/85076259/134823205-fb530b22-ffd3-4b55-8526-c58cf0fdc339.PNG)

Summary statistics, which include: the mean, median, variance, and standard deviation of the PSI, were pulled and are shown above for the suspension coils and for the manufacturing lots. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch (PSI). Based on the variance of the suspension coils in the total summary, the suspension coils overall meet the MechaCar design specifications. However, the lot summary shows that although Lots 1 and 2 meet the design specifications and have variances under 100 PSI, Lot 3 does not meet the design specifications as its variance is much over the 100 PSI limit.

