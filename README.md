# Linear-Logistic-Regression
Implementing Linear and Logistic Regression from scratch

This project contains two parts:
- Part 1: Linear Regression
- Part 2: Logistic Regression

# Part 1: Linear Regression 
# Dataset
In this project, I am using “Boston house prices dataset” from Scikit Learn. The Boston house-price data has been used in many machine learning papers that address regression problems. Learn more at https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html

Boston house prices dataset has 506 instances and for each instance, it has 13 attributes and one target value.
- CRIM per capita crime rate by town
- ZN proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS proportion of non-retail business acres per town
- CHAS Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX nitric oxides concentration (parts per 10 million)
- RM average number of rooms per dwelling
- AGE proportion of owner-occupied units built prior to 1940
- DIS weighted distances to five Boston employment centres
- RAD index of accessibility to radial highways
- TAX full-value property-tax rate per $10,000
- PTRATIO pupil-teacher ratio by town B 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT % lower status of the population
- MEDV Median value of owner-occupied homes in $1000’s

# Part 2: Logistic Regression
# Dataset
In the Logistic Regression part, I am using the “Breast Cancer Wisconsin dataset” , imported from Scikit Learn. The breast cancer dataset is a classic and very easy binary classification dataset which has 569 instances and it has 30 numeric predictive attributes.

Attribute information:
- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry fractal dimension (“coastline approximation” - 1)

The mean, standard error, and “worst” or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.
