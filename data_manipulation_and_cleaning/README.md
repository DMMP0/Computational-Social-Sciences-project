# Data Cleaning

These R Markdown notebooks are used to parse emails into a common format

## Build from enron

This notebook is used to parse emails from the famous enron dataset.
At the moment, it parses only from *_sent_emails* and *personal* folders.

It utilizes the following R libraries:

1. **tidyverse**, for most useful data manipulation
2. **stringr** for string matching and manipulation

## Build from scam 2

This notebook is used to parse emails from the second dataset.

It utilizes the following R libraries:

1. **stringr** for string matching and manipulation

## Pre-process datasets

This notebook is used to parse intermediate datasets into the final one.

It utilizes the following R libraries:

1. **stringi** and **stringr** for string manipulation
2. **dplyr** for tibbles 