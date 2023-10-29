# Boston-Housing-Price-Estimation

This dataset contains information collected by the U.S Census Service concerning housing in the area
of Boston Mass. It was obtained from the StatLib archive (http://lib.stat.cmu.edu/datasets/boston),
and has been used extensively throughout the literature to benchmark algorithms. The dataset is
small and contains information about 506 census tracts of Boston from the 1970 census.
The data was originally published by Harrison, D. and Rubinfeld, D.L. ‘Hedonic prices and the
demand for clean air’, J. Environ. Economics & Management, vol.5, 81-102, 1978.
The Boston Housing dataset contains information about various houses in Boston through different
parameters. There are 13 feature variables in this dataset. The objective is to predict the median
value of prices of the house using the given features.The data has following features, MEDV being the
target variable:

* CRIM - per capita crime rate by town
* ZN - proportion of residential land zoned for lots over 25,000 sq.ft
* INDUS - proportion of non-retail business acres per town
* CHAS - Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
* NOX - nitric oxides concentration (parts per 10 million)
* RM - average number of rooms per dwelling
* AGE - proportion of owner-occupied units built prior to 1940
* DIS - weighted distances to five Boston employment centres
* RAD - index of accessibility to radial highways
* TAX - full-value property-tax rate per USD 10,000
* PTRATIO - pupil-teacher ratio by town
* B - 1000(B - 0.63)**2, where B is the proportion of blacks by town
* LSTAT - percentage of lower status of the population
* MEDV - median value of owner-occupied homes in USD 1000’s

The goal is to build a regression model that can accurately predict the median value of owneroccupied
homes (also known as the target variable MEDV) based on the provided features. The dataset
offers a diverse set of variables, including crime rates, land zoning, air pollution levels, average number
of rooms, and socioeconomic indicators. By analyzing the relationships between these predictors and
the target variable, we can gain insights into the factors that influence housing prices and develop a
predictive model to estimate home values for future observations.

* Note: This project is completed by Fateme Hajizadekiakalaye, Ali Noshad and Ana Drmic for the course of Bayesian Learning and Monto Carlo Simulation at Politecnico di Milano.
