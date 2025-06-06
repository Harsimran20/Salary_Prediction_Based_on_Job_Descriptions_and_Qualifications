💼 Salary Prediction from Job Listings

📌 Overview

This project predicts job salaries based on attributes such as job title, location, company size, experience, industry, and job description using machine learning regression models. It includes preprocessing, model training, evaluation, and feature importance visualization.

🗂️ Project Structure

🧹 Data Preprocessing: Cleaning and imputation of missing values

🛠️ Feature Engineering: Handling numerical, categorical, and textual features

🤖 Modeling: Linear, Ridge, and Lasso Regression

🔍 Hyperparameter Tuning: Grid search with cross-validation

📊 Evaluation: R² and RMSE metrics

🧾 Interpretability: Top features from Lasso coefficients

📁 Dataset

File: job_listings.csv

Target Variable: salary

Features:

🏷️ job_title

🌍 location

🏢 company_size

📈 experience_required

🏭 industry

📝 job_description

🧰 Requirements

Install required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn

🔄 Pipeline Overview
1. 📥 Load and Clean Data
Remove missing salaries

Fill missing values in other fields

2. ⚙️ Feature Preprocessing
🔢 Numerical: StandardScaler

🧮 Categorical: OneHotEncoder

🗒️ Textual: TfidfVectorizer (300 features)

3. 🏋️ Model Training
📐 Linear Regression

📏 Ridge Regression (alpha tuning)

✂️ Lasso Regression (alpha tuning)

4. 📈 Model Evaluation
Metrics used:

📉 RMSE (Root Mean Squared Error)

📊 R² Score

5. 🧠 Feature Importance (Optional)
Visualize non-zero coefficients from Lasso regression

🚀 Usage
Place job_listings.csv in the project directory

Run the script to train and evaluate models

View metrics and feature importance plot

📌 Sample Output

Linear Regression
R² Score: 0.7821
RMSE: 10432.15

Ridge Regression
R² Score: 0.7905
RMSE: 10245.89

Lasso Regression
R² Score: 0.7742
RMSE: 10623.56
📊 Top 20 Lasso features plotted using seaborn.

⚖️ License
This project is intended for educational and research purposes only.
