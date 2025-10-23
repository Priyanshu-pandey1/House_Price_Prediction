🏠 House Price Prediction Model

This is a machine learning project that predicts house prices using a regression model. The goal is to create a model that can accurately estimate the price of a house based on its features.

🛠️ Built With

Python

Scikit-learn

Pandas

NumPy

Matplotlib

Jupyter Notebook / Google Colab

📊 Dataset

This model was trained on the Boston Housing Dataset. This dataset contains various features of houses, such as:

CRIM: Per capita crime rate by town

ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS: Proportion of non-retail business acres per town

CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)

NOX: Nitric oxides concentration (parts per 10 million)

RM: Average number of rooms per dwelling

AGE: Proportion of owner-occupied units built prior to 1940

DIS: Weighted distances to five Boston employment centres

RAD: Index of accessibility to radial highways

TAX: Full-value property-tax rate per $10,000

PTRATIO: Pupil-teacher ratio by town

B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town

LSTAT: % lower status of the population

And the target variable: MEDV (Median value of owner-occupied homes in $1000s)

🤖 Model Performance

A [INSERT YOUR MODEL NAME, e.g., XGBoost Regressor] was used to build the prediction model. The model's performance was evaluated using R-squared error and Mean Absolute Error (MAE).

Training Data Performance

R-squared (R²) error: 0.999 (99.9%)

Mean Absolute Error (MAE): 0.009

Test Data Performance

R-squared (R²) error: 0.905 (90.5%)

Mean Absolute Error (MAE): 2.07

This shows a strong fit on the training data and a very good predictive performance (90.5% R²) on unseen test data.
