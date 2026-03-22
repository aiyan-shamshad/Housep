# 🏠 Housing Price Prediction Project

This project predicts housing prices based on various features using machine learning models.

## 📊 Dataset Overview
- **Shape**: 50,000 rows × 6 columns
- **Features**:
  - SquareFeet
  - Bedrooms
  - Bathrooms
  - Neighborhood (Rural=0, Suburb=1, Urban=2)
  - YearBuilt
  - Price (target)

## 🔍 Exploratory Data Analysis

## 🤖 Machine Learning Models
We evaluated 4 different models:

| Model | R² Score | MAE | RMSE |
|-------|----------|-----|------|
| Decision Tree | 0.097 | 58,211 | 72,721 |
| Random Forest | 0.482 | 44,087 | 55,093 |
| SVR | 0.051 | 60,901 | 74,548 |
| Linear Regression | 0.570 | 40,275 | 50,169 |

**Best Model**: Linear Regression (R² = 0.570)

## 🚀 How to Use
1. Clone the repository
   ```bash
   git clone https://github.com/aiyan-shamshad/Housep.git
   ```

## 📓 Jupyter Notebooks

### [Copy_of_Untitled2.ipynb](Copy_of_Untitled2.ipynb)
A comprehensive walkthrough for data exploration, model training, and evaluation on the housing price dataset.

**Main steps covered:**
- Loading and inspecting the dataset
- Data cleaning, transformation, and visualization
- Applying Decision Tree, Random Forest, SVR, and Multiple Linear Regression models
- Model comparison (R², MAE, MSE, RMSE)
- Final prediction using the best saved model

You can interact with this notebook directly in your browser by opening it in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aiyan-shamshad/Housep/blob/main/Copy_of_Untitled2.ipynb)