# MechaCar_Statistical_Analysis
# Overview
In this weeks tasked we were challenged with making a prograam in R to breakdown the data of Prototype cars based on MPG, suspension, PSI, and manufacturing data. We ran tests on the csv files we were provided; calculate the p-values and also visually represent the data.

## Deliverable 1
For delieverable one we wanted to show the MPG of these variables by using linear regression. (image provided below)
<img width="514" alt="p-values_ _coefficients" src="https://user-images.githubusercontent.com/91299736/149679252-9181e45e-729f-45c8-b126-c8fceaacb657.PNG">

## Deliverable 2
In the second deliverable we wanted to show the suspension data for the vehicles provided. (image below)
<img width="865" alt="Suspension_Data" src="https://user-images.githubusercontent.com/91299736/149679288-9a0ee13f-0cee-433f-9efc-dc04e888fbc8.PNG">

## Deliverable 3 (t-test)
This is the demostration of the t-test function on the PSI measurements (image below)
<img width="448" alt="Alternate_hypothesis" src="https://user-images.githubusercontent.com/91299736/149679598-f4adc76b-022e-4e0a-b798-8389470ff77e.PNG">
The results of the t-test analysis reveals that the p-value for all lots is 0.06028 which is outside the signifigance level of 0.05 resulting in a confidence interval of 93.972%. Based on this prediction, there is not sufficient evidence to reject the null hypothesis. It may be stated that the dataset mean and the population mean are statistically similar. Also, the analysis predicts that the suspension coils dataset is statistically representative of the population mean.

### Study Desgin
The plan is to design the MechaCar vehicle to perform better than the general marketplace vehicles. To accomplish this goal I believe atttention is best served improving the fuel efficiency of the MechaCar. Data needs to be gathered for all MechaCar manufacturing designs, in addition to the current six variables from this analysis. Additional data could include weather conditions, i.e. wind sheer, rain, heat, etc. Varying distances of short trips and long trips are also needed to determine fuel efficiency, as well as fuel efficiency over time. The dataset must include general marketplace competitor's data for comparison.
# Summary
The Goal is to design a MechaCar that is efficient in the most cost-effective ways. MPG, PSI and suspension lets us look at the parts of a car that is likely to fail or lead to sub-par performance.Data needs to be gathered for all MechaCar manufacturing designs, in addition to the current six variables from this analysis. Additional data could include weather conditions, i.e. wind sheer, rain, heat, etc. Varying distances of short trips and long trips are also needed to determine fuel efficiency, as well as fuel efficiency over time.

HO: There is no statistical difference between the competition's mpg dataset and MechaCar's mpg dataset.

Ha: The true mean of MechaCar's mpg is greater than the mean of the competitor's mpg.

The p-value would be set at 0.05. Data that results in a prediction of a p-value smaller than 0.05 would provide predictive evidence that the null hypothesis could be rejected and state that the Ha is true. Providing evidence that the Ha is true would also predict that the MechaCar provides consistently better fuel efficiency than the competitors mpg. There is always room for error and better fuel efficiency may not happen all of the time, but at least 95% of the time.

this concludes my analysis PEM
