# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG

The image below shows results of a statistical analysis using RStudio. This test shows multiple linear regression analysis of vehicle MPG versus vehicle length, weight, spoiler angle, ground clearance, and all wheel drive configuration. MPG is the independant variable.  

![Multiple Linear Regression Results](https://github.com/XSR700/MechaCar_Statistical_Analysis/blob/main/Multiple_Linear_Reg_Deliverable1.PNG)

Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results, vehicle length and ground clearance (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. In other words the vehicle length and ground clearance have a significant impact on MPG.

## Summary Statistics on Suspension Coils

Based on the image of statistical results below, we see that the PSI variance is 62.3 across all lots. This falls below the required 100 PSI variance and meets the MechaCar suspension specification. 

![Total Summar](https://github.com/XSR700/MechaCar_Statistical_Analysis/blob/main/Total_Summary.PNG)

The next image shows the statistical summary of each lot. The results are ordered lot 1, lot 2, and lot 3 respectfully. The 4th row describes the PSI variance of each lot. Lots 1 & 2 show very little variance. Lot 1 seems to have the least variance with 0.98. However, lot 3 has a PSI variance of 170.29 and does not meet the MechaCar suspension specification. 

![Lot Summary](https://github.com/XSR700/MechaCar_Statistical_Analysis/blob/main/Lot_Summary.PNG)


## T-Tests on Suspension Coils

The first image is the result of a one-sample T-test across all suspension coil PSI readings. With a p-value significantly less than 0.05 we can say that we have evidence to reject the null hypothesis and that there is a statistical difference between the observed sample mean and population mean. 

![T-test on all](https://github.com/XSR700/MechaCar_Statistical_Analysis/blob/main/Suspension%20coil%20t-test.PNG)

This next image shows the suspension coil one-sample t-test for each lot. The p-value for lots 1 and 2 are higher than 0.05 and thus we do not have evidence to reject the null hypothesis. However, the p-value for lot 3 is 0.041 and thus we have evidence to reject the null hypothesis. Lot 3 has statistical evidence of a difference between the observed sample mean and population mean. 

![T-Test on each lot](https://github.com/XSR700/MechaCar_Statistical_Analysis/blob/main/Suspension%20coil%20t-test%20of%20each%20lot.PNG)

## Study Design: MechaCar vs Competition

In order for the MechaCar to be sucessful, we need to look at what makes other vehicles post production. This process will involve hypothesis testing on multiple variables. examining one variable is not enough for a complex product with numerous statistics crossing each other. For example, horsepower can have a negative correlation on a quarter mile time of a car while the weight of the car is actualy impacting this correlation. 

For this study I would start with looking at the most sold vehicles in the lot. Then determine which variable stands outs from majority of the vehiles. For example if safety rating was highest among these vehicles then this would be the dependent variable. 

From here on I will take the example of safety rating varible to explain the rest of the study. Safety rating will be tested against sales. The null hypothesis statement would be "Safety rating does not make a difference on how much the car is sold". The alternative hypothesis would be "Safety rating does make a difference on how much the car is sold".

I would then peform two seperate statistical tests for linear regression line and calculate the p-values along with r squared values. The first test would be the linear regression line between safety rating and sales. The second test would be multiple linear regression. The multiple linear regression test would be between other potentially impacting factors such as mpg, vehicle cost, horsepower, and acceleration time. These additional variables are common metrics for consumers when choosing a car. Therefore they are expected to statistically effect the correlation between safety rating and sales. I would look at each independent variable to determine if there is a significant relationship with the dependent variable (safety rating). once we have evaluated each independent variable, I'll evaluate the r-squared value of the model to determine the model sufficiently predicts our dependent variable.

The data needed for this study would be the sale numbers of each individual car model in the dealership. A bigger sample size is better. Additionally the safety rating for each model must be recorded. Each rating must have identical process procedures that established the final rating on each vehicle. 


