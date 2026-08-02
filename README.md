# 🏥 Medical Insurance Cost Prediction using Linear Regression

## 📌 Project Overview

This project uses **Machine Learning** to predict individual medical insurance charges based on personal and demographic information. The model is built using **Linear Regression** and follows a complete data science workflow, from data exploration to model evaluation.

The dataset contains information about customers such as age, gender, BMI, number of children, smoking status, region, and their medical insurance charges.

---

## 🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the data
- Encode categorical variables
- Train a Linear Regression model
- Evaluate the model using regression metrics
- Understand which factors have the greatest impact on insurance costs

---

## 📊 Dataset

### Features

| Feature | Description |
|----------|-------------|
| Age | Age of the insured person |
| Sex | Male or Female |
| BMI | Body Mass Index |
| Children | Number of dependents covered |
| Smoker | Smoking status (Yes/No) |
| Region | Residential region |
| Charges | Medical insurance cost (Target Variable) |

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```
Medical-Insurance-Prediction/
│
├── insurance.csv
├── Medical_Insurance_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Machine Learning Workflow

### 1. Import Libraries

Load the required Python libraries for data analysis and machine learning.

### 2. Load Dataset

Read the insurance dataset using Pandas.

### 3. Exploratory Data Analysis (EDA)

- Dataset overview
- Missing value check
- Summary statistics
- Correlation analysis
- Distribution plots
- Boxplots
- Pairplots

### 4. Data Preprocessing

- Encode categorical variables
- Split features and target
- Train/Test split

### 5. Model Building

Train a **Linear Regression** model using Scikit-learn.

### 6. Model Evaluation

Evaluate the model using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 7. Predictions

Predict insurance charges for unseen customer data.

---

## 📈 Expected Insights

This project helps answer questions such as:

- How much does smoking increase insurance costs?
- Does BMI significantly affect medical expenses?
- Which variables are the strongest predictors of insurance charges?
- How accurately can a Linear Regression model estimate medical costs?


## 📊 Example Prediction

Input:

- Age: 35
- Sex: Male
- BMI: 28.5
- Children: 2
- Smoker: No
- Region: Northwest

Output:

```
Predicted Insurance Charges: $7,850
```

*(Example only; actual results depend on the trained model.)*

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Linear Regression
- Model Evaluation
- Predictive Analytics
- Python Programming
- Machine Learning with Scikit-learn

---


---

## ⭐ Acknowledgements

- Kaggle Medical Insurance Dataset
- Scikit-learn Documentation
- Pandas Documentation
- Matplotlib & Seaborn Documentation
