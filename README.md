# House Price Prediction using XGBoost Regressor

## Description
This project implements a machine learning model to predict housing prices using the **Boston Housing Dataset**. The model leverages **XGBoost Regressor** to provide accurate predictions based on various features like crime rate, number of rooms, and property age. The project demonstrates key machine learning concepts including data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

## Dataset
The dataset used in this project is the **Boston Housing Dataset**, which contains information on various attributes of houses in Boston. The features include:
- **CRIM**: Crime rate per capita
- **ZN**: Proportion of residential land zoned for large lots
- **INDUS**: Proportion of non-retail business acres
- **CHAS**: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- **NOX**: Nitrogen oxides concentration
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built before 1940
- **DIS**: Weighted distance to employment centers
- **RAD**: Index of accessibility to radial highways
- **TAX**: Property tax rate
- **PTRATIO**: Pupil-teacher ratio
- **B**: Proportion of people of African American descent
- **LSTAT**: Percentage of lower status population
- **PRICE**: Median value of homes

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/midhunsomu/house-price-prediction.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Load the dataset and perform **data preprocessing** to handle missing values and normalize features.
2. Conduct **exploratory data analysis (EDA)** and visualize correlations using heatmaps.
3. Split the data into training and testing sets using **train_test_split**.
4. Train the **XGBoost Regressor** model on the training data and evaluate its performance using metrics such as **R² score** and **Mean Squared Error (MSE)**.
5. Visualize the model's predictions versus actual values using scatter plots.

### Example Command:
```bash
python house_price_prediction.py
```

## Model Evaluation
- **Training R² Score**: 0.9999  
- **Testing R² Score**: 0.9999  
- **Mean Squared Error (Training)**: 0.0091  
- **Mean Squared Error (Testing)**: 0.0091  

## Technologies Used
- **Python**: Main programming language.
- **XGBoost**: Model for regression tasks.
- **Scikit-learn**: For data preprocessing, splitting, and metrics.
- **Matplotlib & Seaborn**: For data visualization.

---
