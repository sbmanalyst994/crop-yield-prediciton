# Crop Yield Prediction - NovaGreen Capstone

## Project Overview
This project, **Crop Yield Prediction, A NovaGreen Capstone Led by me**, focuses on predicting crop yield using machine learning.  
The goal is to understand how environmental and Temperature affect crop productivity and to build models that can estimate yield based on those factors.  
The project combines data cleaning, analysis, and model development to support data-driven farming decisions.


## Dataset
- **File used:** `yield_df.csv`  
- Contains agricultural data such as Pesticides, rainfall, temperature, and other environmental factors.  
- The dataset was cleaned by:
  - Dropping unnecessary columns like `Unnamed: 0`
  - Checking for missing values and data types
  - Removing constant or duplicate features



## Methodology

### 1. Data Preparation
- Imported and explored the dataset using `pandas` and `numpy`
- Checked for missing values and removed irrelevant data
- Verified the shape and consistency of the dataset

### 2. Exploratory Data Analysis (EDA)
- Used visualizations to understand relationships between variables and yield  
- Plotted distributions, correlations, and trends using:
  - Heatmaps
  - Pair plots
  - Boxplots

### 3. Feature Engineering
- Encoded categorical features  
- Scaled numerical columns for better model performance  
- Selected features that strongly influence crop yield

### 4. Model Building
Trained and compared several regression algorithms:
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  
- Support Vector Regressor  

Models were evaluated using:
- **R² (Coefficient of Determination)**  
- **MAE (Mean Absolute Error)**  
- **RMSE (Root Mean Squared Error)**

### 5. Model Evaluation
- Compared predicted vs actual yield values  
- Checked feature importance to understand what affects yield the most


## Results
- Random Forest and XGBoost produced the best accuracy among all models.  
- Factors like rainfall, temperature, and pesticides used had the biggest impact on yield.  
- The workflow can be reused for other crops or regions with minimal changes.



## Tools and Libraries
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**, **XGBoost**
- **Jupyter Notebook**
