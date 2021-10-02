# MechaCar_Statistical_Analysis
## Deliverable1
### Linear Regression to Predict MPG
 After performing a Linear Regression Analysis of the data columns in the MechaCar_mpg.csv, the following questions is to be answered:
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

 - Looking at the results of the linear regression model, the last column shows the p-values for the different variables. 
   We can see that the <b> vehicle length </b> & the <b> Vehicle ground clearance </b> both have p-values much less than the significant level of 
   <b>alpha=0.05%</b>, meaning that we have sufficient evidence to reject the null hypothesis and we can state the the two variables have a significant impact on
   MPG(miles per gallon)
   On the other hand, <b>Vehicale Weight</b>, <b>Spoiler angle</b>, <b>AWD</b>, have p-values that are greater than the significant level of <b>alpha =0.05%</b>. 
   This means that the NULL Hypothesis is valid. Therefore these three variables, have little or no effect on the MPG.





* Is the slope of the linear model considered to be zero? Why or why not?
* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
