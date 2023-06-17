# Demand Forecast for Optimized Inventory Planning

This repository contains the code implementation and analysis for an inventory optimization project using machine learning and predictive analytics. The project aims to develop a solution to optimize inventory management for small and medium businesses.

## Dataset

The project utilizes a dataset obtained from Kaggle titled "Demand Forecast for Optimized Inventory Planning" by oscarm524. The dataset can be found at [this link](https://www.kaggle.com/datasets/oscarm524/demand-forecast-for-optimized-inventory-planning?resource=download). It includes the following attributes:

- `itemID`: Unique identifier for every product
- `brand`: Categorical attribute representing different brands
- `manufacturer`: Categorical attribute representing different manufacturers
- `customerRating`: Numerical attribute indicating customer rating
- `category1`, `category2`, `category3`: Categorical and hierarchical attributes representing product categories
- `recommendedRetailPrice`: Numerical attribute representing the recommended retail price
- `salesPrice`: Numerical attribute representing the actual price point
- `order`: Numerical attribute representing the number of sold units in one transaction
- `transactID`: Categorical attribute connecting orders of different products by a single customer
- `time`: Ordinal attribute representing the timestamp of a product purchase
- `simulationPrice`: Numerical attribute representing the price of a product in the simulation period

## Code Implementation

The code implementation involves several steps, including data loading, data preprocessing, feature engineering, exploratory data analysis (EDA), and model training and evaluation. The main libraries used in the code are `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`. 

The code is structured as follows:

1. Data Loading: The dataset is loaded into separate dataframes.
2. Data Preprocessing: Unnecessary columns are dropped, and the dataframes are merged.
3. Feature Engineering: Additional features such as weekend/weekday and day of the week are created.
4. Exploratory Data Analysis (EDA): Various visualizations are generated to gain insights into the data.
5. Model Training and Evaluation: Multiple regression models are trained and evaluated using mean absolute error (MAE).

## Results

The trained models include Linear Regression, Lasso, Ridge, Decision Tree, and Random Forest. The MAE is calculated for both the training and validation sets. The results of the models are displayed, providing insights into their performance.

## Conclusion

The inventory optimization project demonstrates the application of machine learning and predictive analytics techniques to optimize inventory management for small and medium businesses. The code implementation and analysis provide valuable insights into the dataset and offer a foundation for developing a scalable inventory optimization solution.

Note: This Readme file provides a summary of the project. For a more comprehensive understanding, please review the code and comments in the Jupyter Notebook. 
