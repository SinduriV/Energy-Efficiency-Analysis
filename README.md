# Energy-Efficiency-Analysis
# 🏡 Energy Efficiency Analysis  

## 📌 Overview  
This project analyzes the energy efficiency of **12 different building shapes** simulated in **Ecotect** using statistical and machine learning techniques. The goal is to predict **cooling load** based on key building parameters.  

## 📊 Dataset  
The dataset includes **eight independent features** affecting building energy efficiency:  
- **Relative Compactness** (Continuous)  
- **Surface Area** (Continuous)  
- **Wall Area** (Continuous)  
- **Roof Area** (Continuous)  
- **Overall Height** (Continuous)  
- **Orientation** (Categorical)  
- **Glazing Area** (Continuous)  
- **Glazing Area Distribution** (Categorical)  

### **Target Variable:**  
- **Cooling Load** (Continuous)  

## 🔍 Exploratory Data Analysis (EDA)  
Performed using **R Studio**, including:  
- **Scatterplot Matrices** to visualize relationships  
- **Histograms** for feature distributions  
- **Correlation Analysis** to identify key predictors  

## 📈 Statistical & Regression Analysis  
- **Descriptive Statistics**: Summary of key variables  
- **Correlation Analysis**: Identified strong negative/positive correlations  
- **Linear Regression**: Achieved an **88.7% accuracy** in predicting cooling load  
- **Variance Inflation Factor (VIF) Analysis**: Checked for multicollinearity  

## 🤖 Machine Learning Models  
We implemented various models to improve prediction power:  
- **Perceptrons** – Initial prediction accuracy: **58%**  
- **Support Vector Machines (SVM)**  
- **Neural Networks**  
- **K-Nearest Neighbors (KNN)**  
- **Naïve Bayes Classifier**  
- **Decision Trees & Random Forest**  
- **Boosting Algorithms**  

## 🔥 Key Findings  
✅ **Relative Compactness** strongly influences cooling load  
✅ **Surface Area** and **Roof Area** impact energy efficiency  
✅ **Random Forest & Boosting models** provided the best predictive accuracy  

## 🚀 Technologies Used  
- **Python** (Data Preprocessing, Modeling)  
- **R Studio** (EDA & Statistical Analysis)  
- **Ecotect** (Building Shape Simulation)  
- **Machine Learning** (Scikit-learn, TensorFlow)  

## 📁 Repository Structure  
