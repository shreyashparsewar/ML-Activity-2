# Pune House Price Prediction Using Linear Regression

## Project Overview

This project focuses on predicting residential house prices in Pune using **Linear Regression**, a supervised machine learning algorithm.

The model estimates house prices based on important features such as:
- Total Area (Square Feet)
- Number of Bedrooms (BHK)
- Number of Bathrooms
- Location

The project uses Python libraries for data preprocessing, exploratory data analysis, model training, evaluation and price prediction.

## Project Objectives

- Analyze Pune house price data.
- Clean and preprocess the dataset.
- Handle missing and duplicate records.
- Perform exploratory data analysis.
- Apply Linear Regression.
- Evaluate model performance.
- Predict house prices for new property details.

## Dataset Information

**Dataset Name:** Pune House Data

**Source:** [Pune House Prices Dataset](https://github.com/Arbaaz-Shaikh/House-Prices-Prediction-in-Pune)

**Dataset Format:** CSV

**Features Used:**

| Feature | Description |
|---|---|
| total_sqft | Total house area in square feet |
| bhk | Number of bedrooms |
| bath | Number of bathrooms |
| site_location | Location of the property |
| price | House price in ₹ Lakhs (target variable) |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow

1. **Dataset Loading:** Import the Pune house price dataset.
2. **Data Inspection:** Check dataset shape, columns, data types and statistics.
3. **Data Cleaning:** Remove duplicates and handle missing values.
4. **Feature Engineering:** Convert area and bedroom information into numerical features.
5. **Data Filtering:** Remove invalid and unrealistic values.
6. **Exploratory Data Analysis:** Visualize the relationship between area and house price.
7. **Feature Selection:** Select relevant input features and target variable.
8. **Data Splitting:** Divide data into 80% training and 20% testing.
9. **Data Preprocessing:** Apply median imputation and One-Hot Encoding.
10. **Model Training:** Train a Linear Regression model.
11. **Model Evaluation:** Calculate MAE, MSE, RMSE and R² score.
12. **Price Prediction:** Predict the price of a new house.

## Machine Learning Algorithm

**Linear Regression**

Linear Regression is a supervised machine learning algorithm used to predict continuous numerical values.

In this project, it is used to estimate house prices based on property characteristics.

## Model Evaluation Metrics

The model is evaluated using:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

These metrics help measure the difference between actual and predicted house prices.

## Visualizations

The project includes:

1. Area vs House Price Scatter Plot.
2. Actual vs Predicted House Price Plot.

## Sample Prediction

The notebook demonstrates prediction using the following sample property:

| Property Feature | Value |
|---|---|
| Area | 1000 sq. ft. |
| Bedrooms | 2 BHK |
| Bathrooms | 2 |
| Location | Most frequent dataset location |

The trained model estimates the house price in ₹ Lakhs.

## How to Run the Project

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required libraries if necessary.
4. Run all notebook cells sequentially.
5. View the model evaluation results and sample prediction.

## Project Files

- `ML2 house price.ipynb` – Complete Python implementation.
- `README.md` – Project documentation.

## Conclusion

This project demonstrates how Linear Regression can be used for house price prediction using real-estate features. The dataset is cleaned and processed before training the model. Model performance is evaluated using different regression metrics, and the trained model is used to predict prices for new property details.

---

**Project Domain:** Machine Learning / Real Estate Analytics

**Algorithm:** Linear Regression
