# Weather Data Analysis and Prediction

## Overview

This repository contains an analysis and prediction of average temperature using historical weather [data](https://www.kaggle.com/datasets/alejopaullier/new-york-city-weather-data-2019/data) from kaggle. The analysis includes Exploratory Data Analysis (EDA) and the development of a Linear Regression model to predict average temperature.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Data](#data)
- [EDA](#eda)
- [Modeling](#modeling)
- [Results](#results)
- [Usage](#usage)
- [Note](#note)
  

## Introduction

In this project, we analyze historical weather data to understand various factors affecting average temperature. We use this understanding to build a predictive model using Linear Regression. The goal is to accurately predict the average temperature based on features like maximum temperature, minimum temperature, precipitation, and more.

## Installation

To run the code in this repository, you need to have Python and Jupyter Notebook installed. You can install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```

## Data

The dataset used in this analysis includes the following features:

- `tmax`: Maximum temperature
- `tmin`: Minimum temperature
- `departure`: Departure from normal temperature
- `HDD`: Heating Degree Days
- `CDD`: Cooling Degree Days
- `precipitation`: Precipitation amount
- `new_snow`: New snow amount
- `snow_depth`: Snow depth
- `tavg`: Average temperature (target variable)

## EDA

In the EDA section, we explore the dataset to identify patterns, trends, and relationships between different features. This includes:

- Statistical summary of the data
- Distribution plots
- Correlation analysis
- Visualizations of relationships between features

## Modeling

We use a Linear Regression model to predict the average temperature (tavg). The steps include:

1. Splitting the data into training and testing sets
2. Standardizing the features
3. Training the model on the training set
4. Evaluating the model on the test set

## Results

The model's performance is evaluated using visualizations. Specifically, we plot the actual vs. predicted average temperature along with the model equation and perfect prediction line.

**Plotting Model Equation versus Actual Values**
![image](https://github.com/Trenttzzz/weather-predict-model/assets/141043792/5df1235b-28b8-483a-85c6-555a0a61f648)


## Usage

To run the analysis, open the weather_analysis.ipynb notebook in Jupyter Notebook and execute the cells. The notebook includes:

- Data loading and preprocessing
- EDA
- Model training and evaluation
- Visualizations

## Note

This project was completed with limited knowledge and there may be mistakes in the analysis and modeling. Feedback and suggestions for improvement are appreciated.

