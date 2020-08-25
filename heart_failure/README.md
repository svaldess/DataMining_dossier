# Predicting heart failure with K-Nearest Neihgbor algorithm
## #Healthcare #KNN

The objective is to predict heart failure (target) based on a number of predictors, such as anaemia, diabetes, platelets, high blood pressure, among others. The features are numeric (age, anaemia, level of creatinine_phosphokinase, etc.) or categorical (smoking status, presence of diabetes, sex, etc.)
The target is categorical (0: no heart failure and 1: heart failure).

In the first part of the notebook, I built a classsifier KNN from scratch, ti illustrate the logic behind KNN. A 10-fold cross validation is performed. 
In the second part, I used **sklearn KNeighbors Classifier**, which yields a similar accuracy to the accuracy obtained with my KNN classifier. Recall, Precision and F1 are also calculated.

The data was downloaded from this [source](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data).
