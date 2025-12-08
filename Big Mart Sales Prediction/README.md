🛒 Big Mart Sales Prediction — Machine Learning Project
📌 Overview

This project predicts sales for products across Big Mart outlets using machine learning.
The goal is to help retail businesses optimize:

📦 Inventory management

🏪 Store-level stocking

📈 Revenue forecasting

🎯 Product placement & marketing

You will see a full end-to-end ML workflow, including data cleaning, feature encoding, scaling, modeling, and evaluation.

📊 Dataset Description

A realistic synthetic dataset simulating 1550 Big Mart store product records, with:

Features
Feature	Description
Item_Weight	Weight of the product
Item_Fat_Content	Low Fat / Regular
Item_Visibility	How visible the item is on shelves
Item_Type	Snack Foods, Dairy, Households, etc.
Item_MRP	Maximum retail price
Outlet_Identifier	Store code
Outlet_Size	Small / Medium / Large
Outlet_Location_Type	Tier 1 / Tier 2 / Tier 3
Outlet_Type	Grocery Store / Supermarket Type
Sales	Target variable

The dataset includes realistic statistical distributions and business relationships (higher visibility → lower sales, large outlets → higher sales, etc.).

🧹 Data Preprocessing

The following transformations were applied:

✔ Handling missing values
✔ One-hot encoding for categorical features
✔ MinMax scaling for continuous features
✔ Train-test split (80/20)

🤖 Machine Learning Models

The primary model:

Gradient Boosting Regressor

Chosen for its ability to model complex nonlinear relationships.

Additional models (optional):

Linear Regression

Random Forest Regressor

XGBoost (optional enhancement)

📈 Model Evaluation

Metrics used:

MAE — Mean Absolute Error

RMSE — Root Mean Squared Error

R² Score — Variance explained by the model
