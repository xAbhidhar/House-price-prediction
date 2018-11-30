# House-price-prediction
This project involves the prediction of house pricing using the Boston hosuing dataset.

## Dataset
Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1): 
CRIM: per capita crime rate by town 
  - ZN: proportion of residential land zoned for lots over 25,000 sq.ft. 
  - INDUS: proportion of non-retail business acres per town 
  - CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise) 
  - NOX: nitric oxides concentration (parts per 10 million) 1https://archive.ics.uci.edu/ml/datasets/Housing 123 20.2. Load the Dataset 124 
  - RM: average number of rooms per dwelling 
  - AGE: proportion of owner-occupied units built prior to 1940 
  - DIS: weighted distances to ﬁve Boston employment centers 
  - RAD: index of accessibility to radial highways 
  - TAX: full-value property-tax rate per $10,000 
  - PTRATIO: pupil-teacher ratio by town 
  - B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town 
  - LSTAT: % lower status of the population 
  - MEDV: Median value of owner-occupied homes in $1000s We can see that the input attributes have a mixture of units.
  
# Data Analysis and Preprocessing

## Determined the correaltiom between various features
Pearson’s correlation coefficient is the test statistics that measures the statistical relationship, or association, between two continuous variables. It is known as the best method of measuring the association between variables of interest because it is based on the method of covariance. It gives information about the magnitude of the association, or correlation, as well as the direction of the relationship

Performed data preprocessing and analzed daata using correaltion to pick the best features. Standardized the dataset using StandardScalar function.
Implemented Kfold cross validation.


# Data visualization
used graphs for data visualization like heatmap and histograms.

# Algorithms
Implemented and compared the following algorithms:
  - LinearRegression
  
  Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an explanatory variable, and the other is considered to be a dependent variable. For example, a modeler might want to relate the weights of individuals to their heights using a linear regression model.
Before attempting to fit a linear model to observed data, a modeler should first determine whether or not there is a relationship between the variables of interest. This does not necessarily imply that one variable causes the other (for example, higher SAT scores do not cause higher college grades), but that there is some significant association between the two variables. A scatterplot can be a helpful tool in determining the strength of the relationship between two variables. If there appears to be no association between the proposed explanatory and dependent variables (i.e., the scatterplot does not indicate any increasing or decreasing trends), then fitting a linear regression model to the data probably will not provide a useful model. A valuable numerical measure of association between two variables is the correlation coefficient, which is a value between -1 and 1 indicating the strength of the association of the observed data for the two variables.

A linear regression line has an equation of the form Y = a + bX, where X is the explanatory variable and Y is the dependent variable. The slope of the line is b, and a is the intercept (the value of y when x = 0).


  - KNeighborsRegressor
  
  Some pros and cons of KNN
Pros:

No assumptions about data — useful, for example, for nonlinear data
Simple algorithm — to explain and understand/interpret
High accuracy (relatively) — it is pretty high but not competitive in comparison to better supervised learning models
Versatile — useful for classification or regression
Cons:

Computationally expensive — because the algorithm stores all of the training data
High memory requirement
Stores all (or almost all) of the training data
Prediction stage might be slow (with big N)
Sensitive to irrelevant features and the scale of the data
  - DecisionTreeRegressor
  - Support Vector Machines


# Steps performed during the execution

These are the steps which were performed chronologically in the project:
  - Loading libraries and data
  - Data exploration and Data Visualization
  - Data Preprocessing
    - Data prepration
  - Train and Evalute different models
  - Standardize data and run algorithms again
  - Selected the best algorithm with the minimum RMS value


# Results
Gradient boosting provied us with the best results.

