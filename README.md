# Machine Learning Assignment I

# Task 1: Regression Analysis – CO₂ Emission Prediction

## 1. Project Overview

This project is part of Machine Learning Assignment I. The objective is to develop a Regression model to predict the CO₂ emissions produced by vehicles.

CO₂ emissions are an important environmental issue because they contribute to global warming and climate change. Vehicle emissions depend on different factors such as engine size, fuel type, number of cylinders, and fuel consumption.

In this project, Exploratory Data Analysis (EDA) is performed to understand the dataset and identify important features related to CO₂ emissions. A Multiple Linear Regression model is then developed to predict CO₂ emissions.

---

## 2. Domain Explanation

CO₂ emission prediction belongs to the environmental and automobile domain.

Vehicles produce carbon dioxide mainly through fuel combustion. Vehicles with higher fuel consumption and larger engines may produce more CO₂ emissions.

Machine Learning can help analyze vehicle characteristics and predict the expected CO₂ emissions. This can support better understanding of vehicle efficiency and environmental impact.

---

## 3. Problem Statement

The objective of this project is to create a Regression model that predicts vehicle CO₂ emissions using different vehicle characteristics.

The project includes:

- Performing detailed Exploratory Data Analysis.
- Understanding the distribution of the variables.
- Identifying important features.
- Studying relationships between vehicle characteristics and CO₂ emissions.
- Building a Multiple Linear Regression model.
- Evaluating the model using different regression metrics.
- Discussing the results and important insights.

### Target Variable

`CO2.Emissions`

### Important Features

- Engine Size
- Number of Cylinders
- Fuel Type
- Fuel Consumption
- Fuel Economy

---

## 4. Dataset

The dataset contains information about different vehicles and their fuel consumption characteristics.

Important variables include:

| Variable | Description |
|---|---|
| Engine.Size | Size of the vehicle engine |
| fac.Cylinders | Number of cylinders |
| Fuel.Type | Type of fuel used |
| Fuel.Consumption.City | Fuel consumption in city |
| Fuel.Consumption.Hwy | Fuel consumption on highway |
| Fuel.Consumption.Combined | Combined fuel consumption |
| Fuel.Consumption.mpg | Fuel economy |
| CO2.Emissions | CO₂ emissions produced by the vehicle |

### Dataset Source

Kaggle:

https://www.kaggle.com/datasets/bhuviranga/co2-emissions

---

## 5. Exploratory Data Analysis

The dataset was first inspected to understand its structure and quality.

The following checks were performed:

- Number of rows and columns
- Data types
- Missing values
- Duplicate values
- Statistical summary

### Visualizations

The following visualizations were created:

1. CO₂ Emissions Histogram
2. Engine Size Histogram
3. Fuel Consumption Histogram
4. CO₂ Emissions Boxplot
5. Engine Size vs CO₂ Emissions Scatter Plot
6. Fuel Consumption vs CO₂ Emissions Scatter Plot
7. Fuel Economy vs CO₂ Emissions Scatter Plot
8. Fuel Type vs Average CO₂ Emissions Bar Chart
9. Number of Cylinders vs Average CO₂ Emissions Bar Chart
10. Correlation Heatmap
11. Actual vs Predicted CO₂ Emissions Plot

### EDA Insights

The EDA helps identify the relationship between vehicle characteristics and CO₂ emissions.

In general, larger engine sizes and higher fuel consumption are associated with higher CO₂ emissions. The correlation heatmap is used to identify relationships between numerical variables.

The scatter plots provide a visual understanding of how different vehicle characteristics are related to CO₂ emissions.

---

## 6. Machine Learning Model

### Algorithm

**Multiple Linear Regression**

Multiple Linear Regression is used because CO₂ emissions are a continuous numerical variable.

The selected features are used to predict the CO₂ emissions of a vehicle.

### Data Preprocessing

The following preprocessing steps were performed:

- Selected relevant features.
- Checked missing values.
- Converted categorical variables into numerical values using one-hot encoding.
- Divided the dataset into training and testing sets.

### Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

---

## 7. Model Evaluation

The model was evaluated using the following regression metrics:

### MAE – Mean Absolute Error

MAE measures the average absolute difference between the actual and predicted CO₂ emissions.

A lower MAE indicates smaller prediction errors.

### MSE – Mean Squared Error

MSE calculates the average squared difference between actual and predicted values.

A lower MSE indicates better performance.

### RMSE – Root Mean Squared Error

RMSE is the square root of MSE and represents the prediction error in the same unit as CO₂ emissions.

A lower RMSE indicates better performance.

### R² Score

R² Score indicates how much of the variation in CO₂ emissions is explained by the regression model.

A higher R² value indicates better model performance.

---

## 8. Results and Discussion

The regression model was developed to predict CO₂ emissions based on vehicle characteristics.

The EDA showed useful relationships between CO₂ emissions and variables such as engine size and fuel consumption.

The model was evaluated using MAE, MSE, RMSE, and R² Score. The actual metric values are available in the Jupyter Notebook.

The Actual vs Predicted graph was also used to visually compare the model predictions with the actual CO₂ emission values.

---

## 9. Key Insights

- Engine size has an important relationship with CO₂ emissions.
- Higher fuel consumption is generally associated with higher CO₂ emissions.
- The number of cylinders can influence vehicle emissions.
- Fuel type can affect average emission levels.
- The heatmap helps identify relationships between numerical features.
- Regression can be used to estimate CO₂ emissions from vehicle characteristics.

---

## 10. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

---

## 11. Project File

```text
CO2_Regression_Assignment.ipynb
