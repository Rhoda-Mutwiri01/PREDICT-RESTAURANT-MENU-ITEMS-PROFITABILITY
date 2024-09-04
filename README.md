# Restaurant Menu Item Profitability Analysis

This project analyzes and predicts the profitability of restaurant menu items using neural networks.

## Objectives

- To identify features that influence the profitability of menu items.
- To build a neural network model to predict the profitability category (High, Medium, Low) of menu items.

## Data

The dataset contains the following columns:

- `RestaurantID`: Identifier of the restaurant.
- `MenuCategory`: Category of the menu item (Appetizers, Main Course, Desserts, Beverages).
- `MenuItem`: Name of the menu item.
- `Ingredients`: List of ingredients used in the menu item (confidential data included for beverages).
- `Price`: Price of the menu item in dollars.
- `Profitability`: Target variable indicating menu item profitability (High/Medium/Low).

## Methods

- Data Preprocessing
- Feature Engineering
- Model Training and Hyperparameter Tuning
- Model Evaluation using accuracy, precision, recall, and F1 score.

## Results

- **Accuracy**: 66.50%
- **Precision**: 59.88%
- **Recall**: 66.50%
- **F1 Score**: 61.41%

## Conclusion

The model shows moderate performance with room for improvement through further feature engineering, hyperparameter tuning, and model optimization.

## Files

- `Restaurant_Menu_Profitability_Analysis.ipynb`: The Jupyter notebook containing the analysis and model training.
