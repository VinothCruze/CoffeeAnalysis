# CoffeeAnalysis

# Project Overview

In this project, Analyzing coffee data from Kaggle for the quality predictions based on the characteristics in the dataset.

## Project Steps:
## Explorative Data Analysis(EDA):
* Statistical Analysis of the dataset and coming up with assumptions.
* Data cleaning.
* Determine the neccessary characteristics columns useful for the preiction and clustering.

## Quality Prediction
* Prepare dataset by standardizing, applying PCA and data splitting.
* Compare performance to the scikit-learn supervised algorithm
* Tuning the hyper parameters and then apply back the best hyperparameter to the model.
* Created a model and provide inputs to get the score of the coffee.

## Clustering

* Algorithm for K Means Clustering
* FInd optimal clusters
* Plot the clusters
* Correlate the clusters with data to find which parameters aid the total.cup.score of the coffee.

## Code

You can find the code for this project [here](https://github.com/VinothCruze/CoffeeAnalysis/blob/main/Coffee_Quality_Analysis.ipynb).

File overview:

* "Coffee_Quality_Analysis.ipynb" - the full code from this project

# Local Setup

## Installation

To follow this project, please install the following locally:

* Python 3.8+
* Python packages
    * pandas
    * numpy
    * scikit-learn
    * matplotlib
    * seaborn
    
## OR 

## Can be used in Google colab directly 


## Data

Used data from Kaggle, which can be downloaded [here](https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi).  Majorly used merged_data_cleaned.csv.csv and arabica_data_cleaned.csv.
