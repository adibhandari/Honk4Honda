# Honk4Honda

Honk4Honda is a project to predict favorable markets for Honda to expand to using unsupervised learning.

## Background

Honda has identified Omaha, NE as a favorable market for expansion. What other similar markets can Honda expand to.

## Data

Data for car listings on craigslist similar to the [Used Cars Kaggle dataset](https://www.kaggle.com/austinreese/craigslist-carstrucks-data).

## Process

Data cleaning (a lot of it) and exploratory data analysis is outlined in data_analysis.ipynb. Modeling is done in 2 stages - vectorization in modeling_1.ipynb and clustering in modeling_main.ipynb. The resultant clusters can be seen below

![pie_chart](https://github.com/adibhandari/Honk4Honda/blob/master/cluster.PNG)

## Prerequisites

* Python 3.7
* Jupyter Notebook
* sklearn
* seaborn
* matplotlib

