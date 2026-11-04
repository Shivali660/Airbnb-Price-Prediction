# Airbnb Price Prediction – Machine Learning Project

## Project Overview
This project analyses Airbnb listing data and develops a Machine Learning model to predict the prices of Airbnb accommodations in New York City.

The project combines Exploratory Data Analysis (EDA), data preprocessing, model building, hyperparameter tuning, and model evaluation to understand pricing patterns and predict listing prices.

## Objectives
- Explore Airbnb listing data and identify pricing patterns.
- Understand the relationship between listing characteristics and prices.
- Build machine learning models to predict Airbnb prices.
- Compare different regression algorithms.
- Improve model performance using hyperparameter tuning.

## Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Analysed listing characteristics and price distributions.
- Explored price variations across neighbourhood groups.
- Investigated room types and availability patterns.
- Identified outliers and important trends.

### 2. Data Preprocessing
- Prepared data for machine learning.
- Encoded categorical variables using One-Hot Encoding.
- Split the dataset into training and testing sets.

### 3. Machine Learning Models
The following regression models were implemented:

- Linear Regression
- Random Forest Regressor
- Tuned Random Forest Regressor using GridSearchCV

### 4. Model Evaluation

Models were evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 45.521 | 59.504 | 0.388 |
| Random Forest | 43.108 | 58.035 | 0.418 |
| Tuned Random Forest | 42.712 | 57.089 | 0.437 |

### 5. Results
The Tuned Random Forest Regressor performed best among the three tested models.

- Best R² Score: 0.437
- MAE: 42.712
- RMSE: 57.089

The model also supports price predictions for new Airbnb listings based on their neighbourhood and room characteristics.

## Key Findings
- Manhattan listings tend to have higher average prices.
- Entire homes/apartments represent a major listing category.
- A small number of extreme price outliers exist.
- Neighbourhood and room type are relevant factors in price prediction.

## Repository Structure

- `EDA.ipynb` – Exploratory Data Analysis
- `ML.ipynb` – Machine Learning and price prediction
- `README.md` – Project documentation

## Conclusion
This project demonstrates an end-to-end machine learning workflow, from data exploration and preprocessing to model development, hyperparameter tuning, and evaluation.

Although the Tuned Random Forest performed better than the other tested models, there is scope for improvement through additional feature engineering, outlier treatment, and experimentation with other algorithms.

---
**Project Type:** Machine Learning | Regression | Predictive Analytics
