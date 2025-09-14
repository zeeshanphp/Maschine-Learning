# Maschine-Learning
This repository contains basic concepts of Maschine Learning which includes details of  Data-Preprocessing, Data-Visualizaton and other core concepts of Python in ML
# What is inside this Repository ?
## Data-Visualization
  + Using Seaborn
  +  Using Plotly
  +  Simple Charts
  +  Animated Charts
  +  Facet Charts
## Missing Values
&nbsp;&nbsp;&nbsp;&nbsp;To check missing values we used two Datasets Titanic and airbnb and missing values have been imputed with following techniques
  +  Using Mean, Median For Numerical Columns
  +  Using Mode For Categorical Columns  
**Using Scikit-Learn**
  +  Simple Imputer
  +  KNN Imputer KNNImputer(n_neighbors=3)
  +  Iterative Imputer IterativeImputer(max_iter=10, random_state=24)

  <!-- Adding sub heading -->
## Outliers
&nbsp;&nbsp;&nbsp;&nbsp;To check outliers we used Titanic Dataset and outliers have been treated with following techniques
  +  Using Boxplot (used IQR Score to visualize outliers)
  +  Using Z-Score 
  +  Using IQR Score
  <!-- Removing Outliers -->
  +  Removing Outliers using median
  +  Removing Outliers using Winsorization
  +  Removing Outliers using Trimming
  +  Imputing Outliers using IQR Score
  <!-- Imputing Outliers -->
  +  Imputing Outliers using Machine Learning (RandomForestRegressor)


## Feature Transformation
&nbsp;&nbsp;&nbsp;&nbsp;To transform features we used Titanic Dataset and features have been transformed with following techniques
  +  Using Yeo-Johnson Transformation
  +  Using Box-Cox Transformation (only for positive values)
  +  Using Quantile Transformation 