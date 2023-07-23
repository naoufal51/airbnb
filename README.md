# Airbnb Data Analysis
This repository contains the code and data for pricing strategy analysis based on Airbnb listings in Los Angeles County. The analysis aims to answer the following questions:

What factors contribute to the price of an Airbnb listing?
Can we predict the price of a listing given its features?
How do the availability and the stay duration impact listing prices?

## Table of Contents

1. **Overview**
2. **Requirements**
3. **Usage**
4. **Notebooks**
5. **Models**
6. **Contributing**
7. **License**

## Overview
The main focus of this project is to explore and analyze Airbnb listings data to gain insights into various aspects of the short-term rental market ans specifically pricing. The repository includes a preprocessing pipeline that handles data cleaning, transformation, and feature engineering, making the data suitable for machine learning algorithms or other data-driven tasks.

## Requirements

* Python 3.7 or higher
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* plotly
* xgboost

## Usage

1. Clone the repository:
``` bash
    git clone https://github.com/naoufal51/airbnb.git
```
2. Download the Airbnb listings dataset (in CSV format) from [Inside Airbnb](http://insideairbnb.com/) and place it in the data/raw/airbnb/ directory.

3. Install the required Python packages using the requirements.txt file:
``` bash
    pip install -r requirements.txt
```

## Notebooks

The analysis is broken down into three parts, each corresponding to a question listed above.

* **Question 1**: The notebooks data_cleaning.ipynb and data_exploration.ipynb in the question_1 folder perform data cleaning, exploration, and feature engineering to identify the factors contributing to the price of an Airbnb listing.
* **Question 2**: The notebook model_price.ipynb in the question_2 folder performs additional feature engineering, trains machine learning models, and evaluates their performance for predicting the price of a listing given its features.
* **Question 3**: The notebook data_exploration.ipynb in the question_3 folder analyzes the impact of availability and stay duration on listing prices .

## Data

The data used in this analysis is stored in the data folder. The raw data is located in the raw subfolder, while the preprocessed data is stored in the processed subfolder.

## Models

Trained machine learning models for question 2 are stored in the models/question_2 folder.

## License

This project is licensed under the MIT License. See LICENSE for more information.