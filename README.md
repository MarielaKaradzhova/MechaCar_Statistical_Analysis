# MechaCar Statistical Analysis

Tools: R, RStudio

## Linear Regression to Predict MPG
 ![](https://github.com/MarielaKaradzhova/MechaCar_Statistical_Analysis/blob/main/resources/mpg_regression.png)
 
### Questions of Interest

 1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
    -Vechicle Length, Ground Clearance are statistically significant (0.001).
    
 2. Is the slope of the linear model considered to be zero? Why or why not?
  -No, it is >0 because the relationship between vechicle length, grounf clearance and MPG is statistically significant, therfore the slope cannot be = 0.
  
 3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - This model has the ability to predict the MPG of prototypes effectively based on the R-squared value of 0.7149* (see Linear Regression to Predict MPG). 
  
  *A value of 0.7149 indicates strong predictability because it equals to %71.49 out of %100.
 
 
## Visualizations for the Trip Analysis


### Total Summary DataFrame

 ![](https://github.com/MarielaKaradzhova/MechaCar_Statistical_Analysis/blob/main/resources/total_lot.png)
 
 
 ### Lot Summary DataFrame
 
 ![](https://github.com/MarielaKaradzhova/MechaCar_Statistical_Analysis/blob/main/resources/total_sum.png)



The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

 - Lot 3 displays a large variance, therefore manufacturing is not equally variable between all lots, although lot 1 and 2 show minimal variances,  lot 3(170 PSI) exceeds the maxium stated PSI of 70.

 ![](https://github.com/MarielaKaradzhova/MechaCar_Statistical_Analysis/blob/main/resources/lot_3.png)



# T-Tests on Suspension Coils
### Overview of Data:



![](https://github.com/MarielaKaradzhova/MechaCar_Statistical_Analysis/blob/main/resources/susp_data.png)



The t-test resultsshow that the PSI in all manufacturing lots and each lot individually, are not statistically different ( p-value = 0.6072) from the population mean of 1,500 pounds per square inch.

### Suspension T-test Results
![](https://github.com/MarielaKaradzhova/MechaCar_Statistical_Analysis/blob/main/resources/susp_test.png)
 



# Study Design Questions: MechaCar vs Competition
 1.What metric or metrics are you going to test?
 
 
 2.What is the null hypothesis or alternative hypothesis?
 
 
 3.What statistical test would you use to test the hypothesis? And why?
 
 
 4. What data is needed to run the statistical test?
