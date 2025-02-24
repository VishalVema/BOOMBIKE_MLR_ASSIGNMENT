# Boombikes-MLR-Assignment  
> Multiple Linear Regression applied to the Boombikes bike rental dataset as part of an academic assignment.  

## Table of Contents  
- [Overview](#overview)  
- [Technologies Used](#technologies-used)  
- [Key Findings](#key-findings)  
- [Contact](#contact)  

## Overview  

### Modeling Approach  
This project involves conducting a **Multiple Linear Regression (MLR) analysis** to explore the relationship between various factors and bike rental demand.  

### Context  
The analysis was carried out as part of a **Machine Learning course assignment** to apply regression techniques in a real-world scenario.  

### Objective  
The primary goal is to predict the **number of bike rentals** based on independent variables such as temperature, weather conditions, working days, year, and more.  

### Dataset  
The study utilizes the **Boombikes bike rental dataset** to generate insights and develop a predictive model.  

## Key Findings  

### Model Performance  
- **R-squared value**:  
  - 80.32%
  - This indicates the model effectively explains variance in bike rental demand and generalizes well to new data.
 
- **R-squared Adjusted value**:  
  - 79.38%
  - This indicates the model effectively explains variance in bike rental demand and generalizes well to new data.  

- **Error Metrics**:  
  - The **mean squared error (MSE)** is low, suggesting accurate predictions.  

- **Feature Selection & Interpretation**:  
  - **P-values** and **Variance Inflation Factor (VIF)** were used to identify significant variables.  
  - **Recursive Feature Elimination (RFE)** was applied for automated feature selection.  

### Analysis Process  
The Python notebook follows a structured workflow:  
1. **Data Interpretation & Visualization**  
2. **Preprocessing** (handling missing values, encoding, scaling)  
3. **Model Training & Evaluation**  
4. **Feature Selection** (RFE, p-values, VIF)  
5. **Residual Analysis**  
6. **Performance Assessment on Test Data**  

### Techniques & Libraries Used  
Throughout the analysis, several statistical and machine learning techniques were implemented, including **Exploratory Data Analysis (EDA)**, regression diagnostics, and feature selection. The model was built using the **statsmodels** library.  

## Technologies Used  
- **pandas**  
- **seaborn**  
- **matplotlib**  
- **statsmodels**  
- **scikit-learn**  
- **numpy**  

## Contact  
Developed by [@vishalvema] – Feel free to reach out!  
