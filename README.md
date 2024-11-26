# Advertising Dataset - Linear Regression Project

This project demonstrates the basics of linear regression using the Advertising dataset. The goal is to predict sales based on TV, radio, and newspaper advertising budgets.

## Dataset Description

The dataset contains the following columns:
- `TV`: Advertising budget spent on TV (in thousands of dollars)
- `Radio`: Advertising budget spent on radio (in thousands of dollars)
- `Newspaper`: Advertising budget spent on newspapers (in thousands of dollars)
- `Sales`: Sales generated (in thousands of units)

**Source:** [Kaggle: Advertising Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset)

## Project Objectives
1. Understand the relationship between advertising budgets and sales.
2. Build a simple linear regression model to predict sales using a single feature (TV advertising budget).
3. Extend the model to include multiple features (TV, radio, and newspaper budgets).
4. Evaluate model performance using Mean Squared Error (MSE) and R² score.

## Steps
1. **Load the Dataset**:
    - Import the data using pandas.
2. **Exploratory Data Analysis (EDA)**:
    - Visualize the relationships between the features and the target variable (`Sales`).
    - Plot pairwise relationships using seaborn's `pairplot`.
3. **Model Building**:
    - Build a linear regression model using TV advertising budget as the predictor.
    - Train a multiple linear regression model with all three features (TV, radio, newspaper).
4. **Model Evaluation**:
    - Evaluate the model using Mean Squared Error (MSE) and R² score.
5. **Visualizations**:
    - Plot the regression line for the single-feature model.
    - Compare actual vs. predicted values for the multiple-feature model.

## Required Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Download the dataset from [Kaggle: Advertising Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset).
2. Save the dataset as `Advertising.csv` in your project folder.
3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
