# MechaCar_Analysis

## Purpose of Analysis 
Review data from production team to help the manufacturing team. 
•	Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes 
•	Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots 
•	Run t-tests to determine if the manufacturing lots are statistically different from the mean population 
•	Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings. 

## Linear Regression to Predict MPG
Results: 

![image](https://user-images.githubusercontent.com/107721712/195748805-282fda12-ba7f-45c7-a5b6-33d53936ffe2.png)

•	The vehicle length and vehicle ground clearance are statistically likely to provide non-random amounts of variance to this model, meaning that these two variables can have a significant impact on miles per gallon on the prototype.
•	Since the p value is much smaller than 0.05%, so it is sufficient to reject the null hypothesis. Therefore, the slope is not zero. 
•	The R^2 is 0.7149, so over 71% of the predictions can be determined by the model. This level can be effective. 

## Summary Statistics on Suspension Coils

Total Summary: 
![image](https://user-images.githubusercontent.com/107721712/195752144-7fd5e59a-36c2-49d2-a901-f549688fe528.png)

Lot Summary: 
![image](https://user-images.githubusercontent.com/107721712/195753256-b32af591-a80d-4e98-82eb-0e5055b7bf3c.png)

At the total level, the variance is 62.9, which is lower than the 100 pound per square inch threshold. However, Lot 3 (var 170.29) exceeds the requirement while Lot 1 (0.98)  and 2 (7.47) meets the requirement. 

Below boxplots can also demonstrate the variation for the individual lots. 

![image](https://user-images.githubusercontent.com/107721712/195753207-f91bc5ae-4d08-42a5-9bff-4140d3ceef7f.png)

## T-Tests on Suspension Coils
T-test results for all manufacturing lots: 
![image](https://user-images.githubusercontent.com/107721712/195753549-aebf3184-f38e-4bb1-9ff8-1b796de7e078.png)

The mean shows 1498.78 which aligns with what we see in the summary above. P-value is 0.06, which is higher than the 0.05 cut-off. Therefore, the null hypothesis cannot be rejected. In other words, the mean of all lots is statistically similar to the presumed mean of 1500. 
