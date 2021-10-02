<style>H1{MechaCar_Statistical_Analysis: Blue;}</style>
# MechaCar_Statistical_Analysis
## Deliverable1
### Linear Regression to Predict MPG
 After performing a Linear Regression Analysis of the data columns in the MechaCar_mpg.csv, the following questions is to be answered:
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
   
   Looking at the results of the linear regression model, the last column shows the p-values for the different variables.

Output 1.
![Deliverable_1](https://user-images.githubusercontent.com/85843030/135725287-a6b2f67c-f063-42ec-ad26-300ba1f35789.png)


   We can see that the <b> vehicle length </b> & the <b> Vehicle ground clearance </b> both have p-values much less than the significant level of 
   <b> _&alpha;_ = 0.05%</b>, meaning that we have sufficient evidence to reject the null hypothesis and we can state the the two variables have a significant impact on
   MPG(miles per gallon)
   On the other hand, <b>Vehicale Weight</b>, <b>Spoiler angle</b>, <b>AWD</b>, have p-values that are greater than the significant level of <b> _&alpha;_ =0.05%</b>. 
   This means that the NULL Hypothesis is valid. Therefore these three variables, have little or no effect on the MPG.


* Is the slope of the linear model considered to be zero? Why or why not?


  The slope of a linear regression is decided by the following equation: <b><i>y=kx+m</i></b>. Looking at the output, we can see the intercept
  coefficients, and the p-values. 
  The intercept Coefficients tells us where the y-axis is intersepted, i.e the value of <b><i>m </i></b>.
  
 Output 2. 
![image](https://user-images.githubusercontent.com/85843030/135721849-22257d5f-ee70-4c0d-aea2-92a917294d61.png)
  
 We use the p-value of the summary statistics (Output 1) to see tha <b><i>p-value<<0.05</i></b>, and therefore the libnear regression model has got a slope.

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear regression model shows a <b>r2 value </b> of <b>0.715</b>, meaning around <b>71.5% </b>of the variability of our dependent variable is explained using
linear model. The correlation analysis we have conducted here shows a strong correlation between the variables.
We can further take out the vriables that had little, or no impact to our model.By doing so, and using the same linear regression analysis. In this instance, I have
chosen to leave in the Vehicale weight variance, simply becasue it's p-value was slightly over 0.05.

Output 3.
![image](https://user-images.githubusercontent.com/85843030/135722271-96d6c505-ac4a-42b4-836d-db81b9ad12e2.png)


As seen here, the </b>r2=0.6936 </b>, hence <b>69.4%</b>, which is slightly less than previous but still a strong value.

## Summary Statistics on Suspension Coils

Using <i>Suspension_Coil.csv</i> file, the aim of this analysis is to obtain the statistical summary of the data, in terms of mean, median, variance, and
standard deviation of the suspension coil's PSI column.
the following ouput shows the statistical summary:

Output 4.
![image_2_1](https://user-images.githubusercontent.com/85843030/135727310-5538225e-e22b-4963-babf-8f7d08d6a643.png)


Furthremore, if we create a statistical summary, where we group the Manufacturing_Lots, we get the following data for the 3 Lots:

Output 5.
![image](https://user-images.githubusercontent.com/85843030/135728153-842dab2f-ed02-4bf6-b6e1-6f6f2a7a4020.png)


As shown in Output 5, <b>Lot 3</b> <ins>does not meet</ins> the variance design specifications for the MechaCar suspension, as it exceeds <b>100 pounds/in^2</b>.
Looking at Output 4 again, we can see that the variance is within the limit of 100 pounds/in^2, therefore we can assume that Lot 3 has got significant 
outliers in it's data.
