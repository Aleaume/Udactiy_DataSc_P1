# Udactiy_DataSc_P1
Udacity course Data Scientist - P1: Writing a Data Scientist Blog Post

## Motivations

The goal of this project is to provide a simple Airbnb analysis tool for indiviudal or businesses considering making a property available on Airbnb.
For the purpose of showcasing the city of FLorence, Italy is selected in the code.

The project is splitted in 3 topics, trying to give an answer to the following questions

### Questions
- What occupancy rate can you hope to get from your property on Airbnb ?
- What are the typical prices for airbnb properties ?
- What are the top criteria linked to pricing your property ? (using ML)

### Blog

The project is linked to a blog post, available here:

YYYY

## Installations

The code is 100% python based, written in different notebooks.
Python version used: 3.8.5

Librariries imported:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from IPython import display
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score, mean_squared_error

```

## Files Descriptions

The repository is composed of:
### Datasets
In the Florence folder you can see both the sample and the full csvs containing listings information.

### Data dictionary
Detailing the dataset content

### 1 Exploration Jupyter Notebook
Data_exploration.ipynb is a notebook used during the concetption of the project for tests & development purposes

### 3 Questions Notebooks
- Occupancy.ipynb trying to answer - What occupancy rate can you hope to get from your property on Airbnb ?
- Prices.ipynb - What are the typical prices for airbnb properties ?
- Modeling_price.ipynb - What are the top criteria linked to pricing your property ? (using ML)

## Use of repository & Possible Improvements

The project was realized in the course of the Udactiy nanodegree Data Scientist. However it consist of a good base for any deep-dive and further analysis.
More Fine-tuning of the dataset could be done, especially intending to cleaning the dataset in order to give more features to the Model.

Also, more time could be spent on modeling in order to fine tune the training.

## Licensing, Authors, Acknowledgements, etc.
Sources are referenced in each notebooks.
Here are the main links:

- Airbnb Datasets : http://insideairbnb.com/get-the-data/
- "San Francisco Model" used for and Occupancy rate : http://insideairbnb.com/data-assumptions/
- Data Dictionary: https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=1322284596
- Top 10 Amenities at Airbnb : https://www.airbnb.com/resources/hosting-homes/a/the-amenities-guests-want-25
