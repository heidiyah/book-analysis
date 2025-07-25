# What Makes a Book Sell?

## Overview
This project explores what factors influence book sales. I examined patterns between the units sold and other attributes such as genre, author rating, sales price, and sales ranking. Analysis uncovered an unexpected finding: books by *Intermediate*-rated authors sold more on average than those rated *Excellent*.

## Dataset
The data was found on 
[Kaggle.com](https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings/data).
The source of this dataset is unknown and appears to be poorly curated, which led to challenges such as missing values, unexplained gaps in data, and inconsistent publisher revenue data. These issues limited the reliability of real-world inferences, but served as an opportunity to demonstrate data cleaning, EDA, and statistical testing.

## Tools Used
* **pandas** and **numpy**: for data manipulation
* **matplotlib**: for visualizations
* **scipy** and **scikit**: for statistical testing

## Key Analysis Steps
* Data cleaning: standardized column names, genres, and language codes. Identified and handled missing values and outliers, and performed sanity checks to ensure data quality.
* EDA: compared units sold by genre, author rating, average book rating, and other variables.
* Statistical testing: used the **Kruskal-Wallis** test and post-hoc **Dunn** tests to evaluate differences in sales performance between author groups.

## Conclusions
Despite challenges presented by a low-quality dataset, it was discovered that *Intermediate*-rated authors sold more books on average than *Excellent*-rated authors.

Next steps given a more complete dataset would include controlling for variables such as genre or publisher size to isolate the effect of author rating more closely. I would also explore trends such as book price or units sold over time, and attempt to model predictions assuming such trends existed.
