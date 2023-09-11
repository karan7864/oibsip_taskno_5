```markdown
# Sales Prediction Project

This project involves using machine learning to predict sales based on advertising budgets. We explore and analyze the dataset, preprocess the data, train a Random Forest Regressor model, and evaluate its performance.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Data](#data)
- [Analysis](#analysis)
- [Model](#model)
- [Results](#results)


## Introduction

Sales prediction is a common business problem, and this project aims to predict sales based on advertising expenditures. We use a machine learning model, specifically the Random Forest Regressor, to make predictions. The project includes data analysis, preprocessing, model training, evaluation, and visualization.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/oibsip_taskno_5.git
   cd sales_prediction
   ```

2. Install the required Python libraries. You can use `pip`:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Sales_Prediction.ipynb
   ```

## Data

The dataset used for this project is provided in the "Advertising.csv" file. It contains information about advertising budgets (TV, Radio, Newspaper) and their corresponding sales figures.

## Analysis

- Basic dataset information, including data types and column names, is displayed.
- The top 10 entries of the dataset are shown.
- Data preprocessing is performed, including dropping unnecessary columns.

## Model

- We use the Random Forest Regressor model to predict sales.
- The dataset is split into training and testing sets.
- The model is trained using the training data.
- Sales predictions are made using the trained model.

## Results

- The model's performance is evaluated using the R-squared (R2) metric.
- Sales and forecasted sales distributions are visualized using histograms.

