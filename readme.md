# CO2 Emissions Analysis

## Overview
This project focuses on analyzing CO2 emissions data and building machine learning models to predict:
1. The CO2 emission amount using **Linear Regression**.
2. The emission class using **Logistic Regression**.

The analysis and models are built using Python, with some components implemented from scratch to demonstrate core understanding of machine learning algorithms.

---

## Dataset
The dataset `co2_emissions_data.csv` contains over 7000 records of vehicle data with:
- **Features:**
  - Vehicle make, model, size, engine size, number of cylinders, transmission type, fuel type, and fuel consumption ratings.
- **Targets:**
  - CO2 emission amount (in g/km).
  - Emission class.

---

## Files
1. **`A1.ipynb`**:
   - Jupyter Notebook containing the Python code for data analysis, preprocessing, and the implementation of Linear and Logistic Regression models.

2. **`co2_emissions_data.csv`**:
   - Dataset used for building and evaluating the models.

3. **`Report.pdf`**:
   - A detailed report with the following contents:
     - Team members' names and IDs.
     - Explanations of each requirement.
     - Screenshots of output for every step.

4. **`Assignment 1 [Fall 2024].PDF`**:
   - The assignment description, grading criteria, and submission requirements.

---

## Key Components

### 1. Data Analysis
- **Check for Missing Values:** Ensures data completeness.
- **Check Feature Scaling:** Validates if numeric features are on the same scale.
- **Visualizations:**
  - Pairplot with histograms.
  - Correlation heatmap for numeric features.

### 2. Data Preprocessing
- **Target and Features Separation:** Ensures clarity between inputs and outputs.
- **Categorical Encoding:** Converts categorical features to numerical values.
- **Data Splitting:** Shuffles and splits data into training and testing sets.
- **Feature Scaling:** Standardizes numeric features for consistency.

### 3. Linear Regression
- **From Scratch Implementation:** Uses gradient descent to train the model.
- **Feature Selection:** Selects two features with high correlation to the target but low inter-correlation.
- **Cost Function Visualization:** Plots error improvement across iterations.
- **Evaluation:** Uses R² score to assess model performance.

### 4. Logistic Regression
- **Stochastic Gradient Descent Classifier:** Implements logistic regression for classification.
- **Feature Reuse:** Uses the same two features selected for linear regression.
- **Evaluation:** Calculates model accuracy.

---

## Requirements
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (for preprocessing and metrics only).
- **From Scratch Components:**
  - Gradient Descent for Linear and Logistic Regression.
  - Cost function computation.

---

## Running the Project
1. Open `A1.ipynb` in Jupyter Notebook or a compatible editor.
2. Ensure the dataset `co2_emissions_data.csv` is in the same directory.
3. Execute the cells step by step to:
   - Load and analyze the dataset.
   - Preprocess the data.
   - Train and evaluate the Linear and Logistic Regression models.
4. Refer to `Report.pdf` for detailed results and visualizations.

---

## Authors
- **Rana Essam Ibrahim** (ID: 20210133)
- **Ahmed Yehia** (ID: 20210049)


**TA:** Eng. Sarah El-Nady

