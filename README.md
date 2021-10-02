# MechaCar_Statistical_Analysis
## Deliverable1
### Linear Regression to Predict MPG
 After performing a Linear Regression Analysis of the data columns in the MechaCar_mpg.csv, the following questions is to be answered:
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
   
   Looking at the results of the linear regression model, the last column shows the p-values for the different variables.

![Deliverable_1](https://user-images.githubusercontent.com/85843030/135725287-a6b2f67c-f063-42ec-ad26-300ba1f35789.png)


   We can see that the <b> vehicle length </b> & the <b> Vehicle ground clearance </b> both have p-values much less than the significant level of 
   <b>alpha=0.05%</b>, meaning that we have sufficient evidence to reject the null hypothesis and we can state the the two variables have a significant impact on
   MPG(miles per gallon)
   On the other hand, <b>Vehicale Weight</b>, <b>Spoiler angle</b>, <b>AWD</b>, have p-values that are greater than the significant level of <b>alpha =0.05%</b>. 
   This means that the NULL Hypothesis is valid. Therefore these three variables, have little or no effect on the MPG.


* Is the slope of the linear model considered to be zero? Why or why not?
  The slope of a linear regression is decided by the following equation: <b><i>y=kx+m</i></b>. Looking at the output, we can see the intercept
  coefficients, which are shown below, we can see that non of the intercept values are 0. 
![image](https://user-images.githubusercontent.com/85843030/135721849-22257d5f-ee70-4c0d-aea2-92a917294d61.png)
  
 We can also use the p-value of the summary statistics to see tha p-value<<0.05, and therefore the libnear regression model has got a slope.

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear regression model shows a <b>r2 value </b> of <b>0.715</b>, meaning around <b>71.5% </b>of the variability of our dependent variable is explained using
linear model. The correlation analysis we have conducted here shows a strong correlation between the variables.
We can further take out the vriables that had little, or no impact to our model.By doing so, and using the same linear regression analysis. In this instance, I have
chosen to leave in the Vehicale weight variance, simply becasue it's p-value was slightly over 0.05.

![image](https://user-images.githubusercontent.com/85843030/135722271-96d6c505-ac4a-42b4-836d-db81b9ad12e2.png)


As seen here, the </b>r2=0.6936 </b>, hence <b>69.4%</b>.
