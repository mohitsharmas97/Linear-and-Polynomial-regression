# Predictive Models for Placement and Sales Analysis

## 📌 Overview

This repository contains two machine learning models:
1. **Placement Package Predictor** - Linear Regression model predicting job packages based on CGPA
2. **Ice Cream Sales Predictor** - Polynomial Regression model predicting sales based on temperature

## � Models

### 1. Placement Package Prediction Model (`placement_model.pkl`)
- **Model Type**: Linear Regression
- **Input**: CGPA score
- **Output**: Expected job package (in LPA)
- **Performance**: R² score of 0.8604 (86.04% accuracy)
- **Visualization**:
- ![Screenshot 2025-07-08 000937](https://github.com/user-attachments/assets/ebf39ffb-838a-4a7f-9224-07d21c985b96)



### 2. Ice Cream Sales Prediction Model (`icecream_model.pkl`)
- **Model Type**: Polynomial Regression (degree 2)
- **Input**: Temperature
- **Output**: Predicted ice cream sales
- **Performance**: R² score of 0.9292 (92.92% accuracy) 
- **Visualization**:
![Screenshot 2025-07-08 003317](https://github.com/user-attachments/assets/aa4175d2-fd69-461c-9937-7c6510be17ed)


## 🛠️ Installation

```bash
pip install -r requirements.txt

Requirements:

Python 3.8+
scikit-learn==1.6.1
numpy
matplotlib
seaborn
joblib
