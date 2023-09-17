# Multiple-Linear-Regression
[![](https://img.shields.io/badge/Python-blue?style=for-the-badge)](https://github.com/hamzamohdzubair/redant)
[![](https://img.shields.io/badge/StatisticalModel-MultipleLinearRegression-blueviolet?style=for-the-badge)](https://hamzamohdzubair.github.io/redant/)
[![](https://img.shields.io/badge/Library-Statsmodels-green?style=for-the-badge)](https://docs.rs/crate/redant/latest)
[![](https://img.shields.io/badge/Package-VarianceInflationFactor-orange?style=for-the-badge)](https://crates.io/crates/redant)


![](https://img.shields.io/static/v1?label=&message=HeatMap&color=green)
![](https://img.shields.io/static/v1?label=&message=QQPlot&color=blue)

## Research Question and Purpose of Analysis
Can we predict the Tenure duration of our customers with the variables we have?

## The Goal of the Data Analysis 
The goal of this analysis is to predict customer Tenure based on the information we have about them such as their patterns of use of the services we offer like Bandwidth, Device Protection, and Streaming Movies, as well as the type of contract they have made.

## Technique Justification

The method used in this data analysis is Multiple Linear Regression. Multiple Linear Regression attempts to model the relationship between two or more predictor variables with the target variable by fitting a linear equation to the observed data.

The Assumptions of the Multiple Regression Model are:

a) There is a linear relationship between the dependent and the independent variables

b) The independent variables are not highly correlated to each other (multicollinearity)

c) The residuals are normally distributed

d) The observations are independent of each other

The tool for analysis was Python. Python and its packages are very efficient for visualizations, quick statistical summaries, feature selection methods, and linear regression models. Regression analysis was an appropriate technique to answer my research question since I had a bimodal continuous dependent variable (Tenure) and multiple numeric and categorical independent variables with various amounts values (such as Bandwidth, StreamingTV, InternetServices, etc.). Also, not only did I want to find out about the correlation and the magnitude of the relationship between my predictor and target variables, but also I wanted to utilize this model for future predictions.

## Heatmap

The Heatmap helps to quickly visualize the strength relationship of variables across two axes. 

![image](https://github.com/secil-carver/Multiple-Linear-Regression/assets/77639654/3aae491d-477b-4647-93a0-5a415b135f62)


## Q-Q Plot

Q-Q Plots (Quantile Quantile Plots) are visual representations of a sample distribution against a theoretical distribution. Q-Q plots help us determine if our dataset is following a particular type of probability distribution, such as normal, or exponantial.

![image](https://github.com/secil-carver/Multiple-Linear-Regression/assets/77639654/18e51c98-ad8a-420c-8fb5-bf6f5d982691)

## Model Metrics

R-squared

f-statistic

Residual standard error(RSE)


