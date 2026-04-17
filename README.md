# RentWise: House Rent Prediction

## 📌 Objective

Predict house rental prices using machine learning and identify key factors influencing rent.

## 📊 Dataset

House Rent Prediction Dataset (Kaggle)
~4700+ rental listings with features like bedrooms, sqft, city, furnishing status, etc.

## ⚙️ Approach

* Data cleaning and preprocessing
* Feature engineering (floor_num)
* Handling missing values
* Encoding categorical variables
* Model building using Random Forest
* Log transformation of target variable

## 📈 Results

* Final RMSE: **~26,675**
* Improved performance by ~27% compared to baseline models

## 🔍 Key Insights

* Bathrooms are the strongest predictor of rent
* Mumbai properties have significantly higher rent
* Larger properties (sqft) command higher prices
* Bathrooms influence rent more than bedrooms
* Floor level has moderate impact

## 🛠️ Tools Used

* Python (Pandas, NumPy)
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## 📂 Project Structure

* `notebooks/` → Jupyter notebook
* `data/` → dataset
* `README.md` → project overview

## 🚀 Future Improvements

* Deploy as a Streamlit web app
* Try advanced models (XGBoost)
* Add location clustering
