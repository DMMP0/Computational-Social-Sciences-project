# Models Ensemble

These R Markdown notebooks deals with model tuning, training and testing.

Intermediate steps are saved as RDS to ease the long process.

## Prepare DF

This notebook is used to prepare both training and testing datasets.
Due to high computational times that I cannot personally afford, it only samples 1K emails each.

It utilizes the following R libraries:

1. **tidyverse**, for most useful data manipulation

## Linear Models

This notebook trains Logistic Regression, Linear Discriminant Analysis,
Quadratic Discriminant Analysis and Naive Bayes.

It utilizes the following R libraries:

1. **tidyverse**, for most useful data manipulation
2. **tidymodels**, for logistic regression
3. **MASS**, for LDA and QDA
4. **e1071**, for Naive Bayes

## KNN

This notebook tunes and trains the K-Nearest Neighbours.

It utilizes the following R libraries:

1. **tidyverse**, for most useful data manipulation
2. **tidymodels** and **kknn**, for building the model
3. **ggplot2**, for visualization

## Tree Methods

This notebook trains and tunes Simple classification trees, Pruned trees, Bagged trees,
Random Forests and Boosted Trees.

It utilizes the following R libraries:

1. **tidyverse**, for most useful data manipulation
2. **tree**, for simple and pruned tree
3. **randomForest**, for random forests and bagging
4. **caret**, for boosted trees

## SVM

This notebook trains and tunes Maximal Margin Classifier, Support Vector Classifier,
Radial Support Vector Machine, Sigmoid Support Vector Machine, Polynomial Support Vector Machine..

It utilizes the following R libraries:

1. **tidyverse**, for most useful data manipulation
2. **e1071**, for SVMs
3. **umap**, **dplyr**, **ggplot2** and **plotly** for data visualization.

## Model Assessment

These notebooks evaluate the performance of the models. There are 3 notebooks just for convenience,
in the future I may compress everything into one.

They utilize the following R libraries:

1. All the previously cited ones for predicting
2. **ROCR**, for the ROC curve
3. **caret** specifically, for computing all statistics of the confusion matrix
