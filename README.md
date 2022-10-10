# Linear Regression Analysis on Multiple Factors Related to Demography, Economy, Sociology, and Public Health

This report analyzes what factors of a country significantly impact the nationwide life expectancy using techniques in multiple linear regression.

It examines potential multicolinearity, influential points, heteroscedasticity and non-normality that will make the modeling estimation unreliable. It then
performs feature selection using different approaches involving t test for single predictor, adjusted R squared, Mallow's Cp and backward stepwise BIC.
Lastly, it decides the final optimal model by performing 10-fold cross validation on candidate models and choosing the one with the least total
root-mean-square errors. This final model offers a statistical insight on what factors are primarily responsible for life expectancy and how significant
the impacts are.

The linear_regression.ipynb includes all codes involving data cleaning, exploratory data analysis, regression modeling, statistical tests and feature selection,
and derives the final choice of model at the end. The report.pdf walks through the entire process with tables and visualizations.
