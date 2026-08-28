# Bike Sharing Demand Prediction

## Project Overview

This project focuses on predicting bike-sharing demand using the Seoul Bike Sharing Demand dataset.

The objective is to analyze historical bike-rental data and develop a machine-learning regression model that predicts the number of rented bikes at a given hour.

The dataset contains hourly bike-rental information along with time, weather, seasonal, holiday, and system-operation attributes. The original dataset includes variables such as Date, Rented Bike Count, Hour, Temperature, Humidity, Wind speed, Visibility, Dew point temperature, Solar Radiation, Rainfall, Snowfall, Seasons, Holiday, and Functioning Day.

The project is implemented in Python using a Jupyter Notebook designed to run in VS Code.

---

## Problem Statement

Bike-sharing demand varies throughout the day and can be influenced by temporal patterns, seasons, holidays, weather conditions, and whether the bike-sharing system is functioning.

The project aims to use historical data to:

- Understand bike-rental demand patterns.
- Explore relationships between time-related factors and bike demand.
- Analyze the distribution of rented bikes.
- Examine demand patterns by hour and season.
- Build a regression model for bike-demand prediction.
- Evaluate the prediction performance using standard regression metrics.
- Save the trained model for future use.

---

## Objectives

The main objectives of this project are:

1. Load and understand the Seoul Bike Sharing Demand dataset.
2. Inspect the dataset structure, data types, and quality.
3. Check for missing values and duplicate records.
4. Clean and preprocess the dataset.
5. Convert the date information into useful time-related features.
6. Perform exploratory data analysis.
7. Visualize bike-demand patterns.
8. Analyze numerical correlations.
9. Prepare features and target variables.
10. Split the dataset into training and testing sets.
11. Train a Linear Regression model.
12. Evaluate model performance using MAE, RMSE, and R².
13. Analyze prediction errors.
14. Analyze model coefficients.
15. Save and reload the trained machine-learning model.

---

## End Users

This project can be useful for:

- **Bike-Sharing Operators** – Understand demand patterns and improve operational planning.
- **Transport Planners** – Analyze usage patterns for urban mobility planning.
- **Business Teams** – Support demand-based operational decisions.
- **Data Analysts** – Explore relationships between bike demand and different factors.
- **Machine Learning Students** – Understand an end-to-end regression workflow.
- **Researchers** – Use bike-sharing demand data for further analysis and experimentation.

---

## Dataset

The project uses the **Seoul Bike Sharing Demand** dataset.

The original dataset contains hourly bike-rental observations and includes the following attributes:

| Feature | Description |
|---|---|
| Date | Date of the observation |
| Rented Bike Count | Number of bikes rented |
| Hour | Hour of the day |
| Temperature | Temperature measurement |
| Humidity | Humidity percentage |
| Wind speed | Wind speed measurement |
| Visibility | Visibility measurement |
| Dew point temperature | Dew point temperature |
| Solar Radiation | Solar radiation measurement |
| Rainfall | Rainfall measurement |
| Snowfall | Snowfall measurement |
| Seasons | Season of the year |
| Holiday | Holiday status |
| Functioning Day | Whether the bike-sharing system was functioning |

The dataset contains **8,760 hourly observations** plus the header row.

---

## Dataset Characteristics

The dataset contains:

- **8,760 data records**
- **14 original columns**
- One target variable: `Rented Bike Count`
- Numerical and categorical variables
- Date and time information
- Weather-related variables
- Seasonal and operational information

---

## Technologies Used

The project uses the following technologies and Python libraries:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Joblib**
- **Jupyter Notebook**
- **Visual Studio Code**

### Library Usage

**Pandas**  
Used for data loading, manipulation, cleaning, and analysis.

**NumPy**  
Used for numerical operations and calculations.

**Matplotlib**  
Used for creating data visualizations.

**Seaborn**  
Used for statistical visualizations and exploratory data analysis.

**Scikit-learn**  
Used for preprocessing, train-test splitting, Linear Regression, and model evaluation.

**Joblib**  
Used to save and reload the trained machine-learning model.

---

## Project Workflow

The project follows the following workflow:

```text
Dataset
   ↓
Data Loading
   ↓
Data Inspection
   ↓
Data Cleaning
   ↓
Duplicate / Missing Value Check
   ↓
Date Processing
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Data Preprocessing
   ↓
Linear Regression
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Error Analysis
   ↓
Coefficient Analysis
   ↓
Model Saving
   ↓
Model Reload Verification