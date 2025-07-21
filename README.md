# Solar-Panel-Efficiecny

☀️ Solar Panel Efficiency Prediction
This project aims to predict the energy efficiency of solar panels using various operational and environmental features. It includes end-to-end data preprocessing, feature engineering, and model building for regression analysis using machine learning.

📌 Project Overview
Solar panels are affected by several factors such as irradiance, temperature, age, soiling, and more. This notebook focuses on:

Cleaning and preparing solar panel operation data.

Handling missing values and encoding categorical variables.

Scaling features for optimal model performance.

Building a machine learning model to predict solar panel efficiency.

🧪 Technologies & Libraries Used
Python

NumPy, Pandas – data manipulation

Scikit-learn – model building, preprocessing

Matplotlib / Seaborn – (assumed for visualization if used later)

Jupyter Notebook

🔧 Data Preprocessing Steps
Handled missing values using mean/mode imputation and random selection.

Encoded categorical columns (string_id, error_code, installation_type) using LabelEncoder.

Applied StandardScaler to normalize numerical features.

Ensured all data was numeric using pd.to_numeric().

🧠 Model Building (Assumed from notebook)
(Based on standard practice, if your notebook includes this, feel free to add specific model details)

Applied regression models like Linear Regression, Random Forest, or XGBoost (to be confirmed).

Evaluated using metrics like R², MAE, or RMSE.

📁 Files
train.csv – Training dataset

test.csv – Test dataset

Solar_panel_clearance.ipynb – Complete implementation

🚀 How to Run
Clone the repository

Make sure train.csv and test.csv are in the working directory

Open Solar_panel_clearance.ipynb in Jupyter Notebook

Run the cells sequentially
