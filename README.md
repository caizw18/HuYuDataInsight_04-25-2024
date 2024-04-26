# HuYuDataInsight_04-25-2024
This is the workload for our company HuYuDataInsight LLC on Apr 25, 2024

We use the methods in multiple linear regression to find out the model for the dataset. By reading the data from data1.csv, we find that there are totally 1001 observations 
and 39 variables. Y is the outcome variable, E1 to E8 are the eight environment variables, and G1 to G30 are the thirty genetic independent indicator variables.

It is obvious that the model is related to the multiple linear regression, and the function should include the interactions of some variables. Firstly, we do an analysis of 
multiple linear regression of Y and all other 38 variables in R. Our goal is trying to select the important variables. Secondly, we find optimal lambda for Box-Cox transformation 
of our linear model to let the dataset normally distributed. Thirdly, we consider the interactions of variables and perform stepwise multiple regression to select the significant 
variables that generate our dataset. Lastly, we perform an anova test to get the anova table and the result of our model.
