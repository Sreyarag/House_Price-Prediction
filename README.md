House Price Prediction Using Machine Learning

Project Overview

This project focuses on analyzing housing data and predicting house prices using Machine Learning regression algorithms. The project uses the Ames Housing Dataset, which contains information about residential properties in Ames, Iowa.

The main objective is to identify the important factors influencing house prices and build a reliable model for price prediction.

Objectives

- Perform Exploratory Data Analysis (EDA) on housing data.
- Handle missing values and preprocess the dataset.
- Apply feature engineering to create meaningful features.
- Build and evaluate different regression models.
- Identify important features affecting house prices.
- Develop a house recommendation system based on user requirements.

Dataset

- Dataset: Ames Housing Dataset
- Location: Ames, Iowa, USA
- Records: 1,460
- Features: 79 explanatory variables
- Target Variable: "SalePrice"

Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Machine Learning Algorithms

The following regression algorithms were explored:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor

Gradient Boosting Regressor was selected as the final model based on the initial model comparison.

Data Preprocessing

- Missing value handling
- Categorical feature encoding using OneHotEncoder
- Numerical feature imputation
- Feature engineering
- Train-test splitting
- Pipeline-based preprocessing to prevent data leakage

Feature Engineering

The following new features were created:

- "TotalSF" – Total basement and floor area
- "TotalBath" – Total number of bathrooms
- "HouseAge" – Age of the house
- "RemodAge" – Age since the last remodeling
- "TotalPorchSF" – Total porch area

Final Model Performance

The final Gradient Boosting model achieved the following results on the test dataset:

Evaluation Metric| Result
MAE| 15,922.62
MSE| 711,229,898.04
RMSE| 26,668.89
R² Score| 90.73%
Mean Cross-Validation R²| 87.27%

House Recommendation System

A simple recommendation system was developed to suggest houses based on user preferences such as:

- Budget
- Neighborhood
- Minimum living area
- Number of bedrooms
- Overall house quality

The system uses predicted house prices to filter and recommend suitable properties from the dataset.

Note: Recommendations are based on historical dataset records and do not represent currently available real estate listings.

Project Structure

House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── README.md
└── data.csv

How to Run the Project

1. Clone this repository:

git clone https://github.com/your-username/House-Price-Prediction.git

2. Navigate to the project folder:

cd House-Price-Prediction

3. Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

4. Open Jupyter Notebook:

jupyter notebook

5. Open and run "House_Price_Prediction.ipynb".

Conclusion

This project demonstrates the application of data analysis and machine learning techniques for house price prediction. The final Gradient Boosting model achieved an R² score of 90.73%, showing good predictive performance on the test dataset.

The project also explores how machine learning can help identify important housing features and support data-driven property recommendations.

---

Project Type: Machine Learning | Regression | Data Science
