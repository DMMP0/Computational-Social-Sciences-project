# Sentiment Analysis

This R Markdown notebook is used for further polishing and sentiment analysis.

Intermediate steps are saved as RDS to ease the long process.

This will be used to get the final version of the dataset to feed the models.

## Polishing

It utilizes the following R libraries:

1. **tidyverse**, for most useful data manipulation
2. **stringr** for string matching and manipulation
3. **textstem** for lemmatization
4. **stopwords** for stopword removal
5. **dplyr** for easier dataframe manipulation
6. **wordcloud2** for visualization
7. **tidyr** for dropping NAs

## Sentiments

This notebook is used to parse emails from the second dataset.

It utilizes the following R libraries:

1. **syuzhet** for getting sentiments of subject and body
