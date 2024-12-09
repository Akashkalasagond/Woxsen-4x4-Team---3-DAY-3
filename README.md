# House Data EDA Project

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on the **House Data** dataset. The dataset contains details of houses sold in King County, USA, including information on the price, bedrooms, bathrooms, square footage, and more. The aim of this project is to extract meaningful insights from the data and understand the relationships between various features and house prices.

## Dataset

- **Dataset Name**: House Data
- **Source**: [Kaggle - House Data](https://www.kaggle.com/datasets/shree1992/housedata/data)
- **Description**: This dataset contains 21,613 records and 21 columns, covering housing attributes like price, number of bedrooms, bathrooms, square footage, condition, year built, and location (latitude and longitude).

## Objectives

1. Understand the structure and contents of the dataset.
2. Perform data cleaning and preprocessing to handle missing or erroneous values.
3. Analyze relationships between features such as:
   - How different features like the number of bedrooms, square footage, and location influence house prices.
   - Identifying outliers and anomalies in the dataset.
4. Generate visualizations to uncover patterns and trends.

## Key Features in the Dataset

| Column Name     | Description                                       |
|------------------|---------------------------------------------------|
| `id`            | Unique ID for each house                         |
| `date`          | Date of sale                                     |
| `price`         | Price of the house                               |
| `bedrooms`      | Number of bedrooms                               |
| `bathrooms`     | Number of bathrooms                              |
| `sqft_living`   | Square footage of the living area                |
| `sqft_lot`      | Square footage of the lot                        |
| `floors`        | Number of floors                                 |
| `waterfront`    | Whether the house has a waterfront view          |
| `view`          | Quality of the view                              |
| `condition`     | Overall condition of the house                   |
| `grade`         | Construction grade                               |
| `sqft_above`    | Square footage above ground                      |
| `sqft_basement` | Square footage of the basement                   |
| `yr_built`      | Year the house was built                         |
| `yr_renovated`  | Year the house was renovated                     |
| `zipcode`       | Zipcode of the house                             |
| `lat`           | Latitude                                         |
| `long`          | Longitude                                        |
| `sqft_living15` | Average square footage of living space in nearby houses |
| `sqft_lot15`    | Average lot size of nearby houses                |

## Tools and Libraries Used

- **Programming Language**: Python
- **Libraries**: 
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `matplotlib` and `seaborn` for data visualization
  - `scipy` for statistical analysis

## Insights Derived

1. **Distribution of Prices**: Analyzed how house prices vary across different categories such as location and size.
2. **Feature Importance**: Identified the most influential factors affecting house prices.
3. **Geographical Patterns**: Explored how latitude and longitude correlate with pricing.
4. **Condition and Grade Analysis**: Studied how house quality and condition impact pricing.

## How to Run the Code

1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script provided to execute the EDA.

## Results and Visualizations

Visualizations and results are saved in the `output` directory. These include:
- Correlation heatmap of features.
- Price distribution histograms.
- Scatter plots for key relationships (e.g., `price` vs `sqft_living`).


**Acknowledgments**: 
This dataset was provided by [Shree1992](https://www.kaggle.com/shree1992) on Kaggle.
