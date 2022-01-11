# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG

The variables/coefficients that provided the most non-random amount of variance were when comparing MPG with vehicle length. The image below represents the statistical analysis and linear regression graph of MPG vs. Vehicle Length. this variable showed the lowest p-value (0.0000026).

![MPG vs Vehicle Length](https://github.com/XSR700/MechaCar_Statistical_Analysis/blob/main/mpg%20vs%20vehicle%20length.PNG)


given the p-value we can say the slope of the linear model is not zero and can reject the null hypothesis and say that there is statistically significant probability that vehicle length does affect vehicle mpg. 


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



