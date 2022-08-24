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

