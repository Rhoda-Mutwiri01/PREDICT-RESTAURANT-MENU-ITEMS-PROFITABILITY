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
- Feature Engineering:
     Ingredients Count: Created a feature for the number of ingredients in each menu item.
     Price Category: Categorized menu items into price ranges (Low, Medium, High).
-  Exploratory Data Analysis (EDA):
      Analyzed the distribution of menu items across different categories and their profitability.
      Examined the correlation between ingredients count, price, and profitability.
-  Modeling:
      Neural Networks: Deployed and trained a neural network model to predict menu item profitability.
- Model Training 
     Data Split: Divided data into training (80%) and testing (20%) sets to evaluate model performance.
- Model Evaluation using accuracy, precision, recall, and F1 score.
- Hyperparameter Tuning:
    Objective: To optimize model performance by finding the best combination of hyperparameters.
    Parameters Tuned: Included learning rate, number of hidden layers, number of neurons per layer, batch size, and activation functions.
    Techniques Used: Grid search, random search
    Impact: Improved model performance by fine-tuning parameters to better capture patterns in the data.


## Results

- **Accuracy**: 66.50%
- **Precision**: 59.88%
- **Recall**: 66.50%
- **F1 Score**: 61.41%

## Conclusion

The model shows moderate performance with room for improvement through further feature engineering, hyperparameter tuning, and model optimization.


