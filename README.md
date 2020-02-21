# Recipe2Cuisine

Recipe2Cuisine is a project to predict the cuisine of a recipe

## Background

Objective is to enable users to query recipes by cuisine, not just ingredients. It is infeasible to label all the recipes by hand by hand. Using a small labeled training set, predict the cuisine, identify the driving ingredients, similarities/dissimilarities between ingredients. Deliver a guide for a few major cuisines. 

## Data

Recipes data challenge. The dataset is similar to the [What's Cooking Kaggle dataset](https://www.kaggle.com/c/whats-cooking/data).

## Process

Data cleaning and exploratory data analysis is outlined in data_processing. Modeling is done using a combination of TF-IDF Vectorization and grid search using sklearn in model_training.

## Prerequisites

* Python 3.7
* Jupyter Notebook
* sklearn
* seaborn


