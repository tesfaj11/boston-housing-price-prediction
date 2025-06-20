# boston-housing-price-prediction
A simple linear regression project using the Boston Housing dataset to explore how features like room count, income level, and student-teacher ratio influence home prices.
# Boston Housing Price Prediction – Linear Regression Case Study

This project focuses on predicting housing prices using the Boston Housing dataset. The goal was to apply simple linear regression to understand how different features of a home or neighborhood influence its market value.

## Files Included
- `boston.csv`: The dataset used in this analysis
- `Boston Housing Case Study.ipynb`: Jupyter Notebook containing all steps, code, and explanations
- `README.md`: Project summary

## Objective
The goal of this case study is to predict the median home value (`MEDV`) using a few key features:
- `RM`: Average number of rooms per home
- `LSTAT`: Percentage of lower income population
- `PTRATIO`: Student-to-teacher ratio in the town

## What I Did
1. Loaded and reviewed the dataset
2. Checked for missing values
3. Explored data distributions and relationships
4. Identified features that were most correlated with home prices
5. Split the data into training and test sets
6. Built and trained a linear regression model
7. Evaluated the model’s performance using R² and RMSE
8. Interpreted the results and wrote a summary

## Results
- R² Score: 0.63 — The model explains about 63% of the variation in home prices
- RMSE: Approximately 5.21 — On average, predictions were off by about $5,210

## Takeaways
- Homes with more rooms tend to be more expensive
- Higher poverty levels and larger class sizes are associated with lower home values
- Linear regression gives a good starting point, but there’s room to improve accuracy with more advanced models

## Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
