# MechaCar_Analysis

## Purpose of Analysis 
Review data from production team to help the manufacturing team. 
•	Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes <br /> 
•	Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots <br /> 
•	Run t-tests to determine if the manufacturing lots are statistically different from the mean population <br /> 
•	Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings. <br /> 

## Linear Regression to Predict MPG
Results: 

![image](https://user-images.githubusercontent.com/107721712/195748805-282fda12-ba7f-45c7-a5b6-33d53936ffe2.png) <br /> 

•	The vehicle length and vehicle ground clearance are statistically likely to provide non-random amounts of variance to this model, meaning that these two variables can have a significant impact on miles per gallon on the prototype.<br /> 
•	Since the p value is much smaller than 0.05%, so it is sufficient to reject the null hypothesis. Therefore, the slope is not zero. <br /> 
•	The R^2 is 0.7149, so over 71% of the predictions can be determined by the model. This level can be effective. <br /> 

## Summary Statistics on Suspension Coils

Total Summary: <br /> 
![image](https://user-images.githubusercontent.com/107721712/195752144-7fd5e59a-36c2-49d2-a901-f549688fe528.png)

Lot Summary: <br /> 
![image](https://user-images.githubusercontent.com/107721712/195753256-b32af591-a80d-4e98-82eb-0e5055b7bf3c.png)

At the total level, the variance is 62.9, which is lower than the 100 pound per square inch threshold. However, Lot 3 (var 170.29) exceeds the requirement while Lot 1 (0.98)  and 2 (7.47) meets the requirement. <br /> 

Below boxplots can also demonstrate the variation for the individual lots. 

![image](https://user-images.githubusercontent.com/107721712/195753207-f91bc5ae-4d08-42a5-9bff-4140d3ceef7f.png)

## T-Tests on Suspension Coils
T-test results for all manufacturing lots: <br /> 
![image](https://user-images.githubusercontent.com/107721712/195753549-aebf3184-f38e-4bb1-9ff8-1b796de7e078.png)

The mean shows 1498.78 which aligns with what we see in the summary above. P-value is 0.06, which is higher than the 0.05 cut-off. Therefore, the null hypothesis cannot be rejected. In other words, the mean of all lots is statistically similar to the presumed mean of 1500. <br /> 


![image](https://user-images.githubusercontent.com/107721712/195754125-2cd7fc22-2c21-4655-a227-a523e6e2ffa6.png)<br /> 
![image](https://user-images.githubusercontent.com/107721712/195754413-069e5761-6721-49a3-bacf-f5d235834a50.png)<br /> 
![image](https://user-images.githubusercontent.com/107721712/195754506-6bfe16a2-f134-435a-8570-4a9d33acb521.png)<br /> 
•	Lot 1 has actual sample mean of 1500. With p-value of 1, we cannot reject the null hypothesis. Therefore, there is no statistical difference between the sample and the population mean. <br /> 
•	Lot 2 has actual sample mean of 1500.02. With p-value of 0.61, we cannot reject the null hypothesis. Therefore, there is no statistical difference between the sample and the population mean.<br />  
•	Lot 3 has actual sample mean of 1496.14. With p-value of 0.04, we can reject the null hypothesis. <br /> 


## Study Design: MechaCar vs Competition

This study is to compare models from different manufacturers in the past 3 years to understand what factors determine the selling price. 
Metrics: <br /> 
•	Current selling price <br /> 
•	Safety Features Rating <br /> 
•	Annual cost of maintenance <br /> 
Hypothesis: <br /> 
•	Null: MechaCar is priced base don its key factors <br /> 
•	Alternative: MechaCar is not priced correctly per key factors <br /> 
Statistical tests: <br /> 
A multiple linear regression to indicate the factors with highest correlation to the selling price. 
