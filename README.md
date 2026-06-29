# 🚲 Bike Rental Demand Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the **Rented Bike Count** using multiple Machine Learning regression algorithms. Accurate bike demand forecasting helps bike-sharing services optimize fleet allocation, reduce operational costs, and improve customer satisfaction.

The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of different regression algorithms.

---

## 📂 Project Structure

```
Bike-Rental-Demand-Prediction/
│
├── pre_processed.pkl                 # Preprocessed dataset
├── EDA.ipynb                         # Exploratory Data Analysis
├── Linear_Regression.ipynb           # Linear Regression Model
├── Regression_Tree.ipynb             # Decision Tree Regressor
├── Random_Forest_Regressor.ipynb     # Random Forest Model
├── XGBoost_Regressor.ipynb           # XGBoost Model
└── README.md
```

---

## 📊 Dataset

The dataset contains environmental and temporal information affecting bike rentals.

### Features include:

* Temperature
* Humidity
* Wind Speed
* Visibility
* Solar Radiation
* Rainfall
* Snowfall
* Seasons
* Holiday
* Functioning Day
* Hour
* Month
* Day
* Year

### Target Variable

* **Rented Bike Count**

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA notebook includes:

* Data cleaning
* Missing value analysis
* Distribution of numerical variables
* Correlation analysis
* Feature relationships
* Outlier visualization
* Bar plots
* Histograms
* Box plots
* Heatmaps

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

* Handling missing values
* Feature encoding
* Feature selection
* Multicollinearity analysis
* Data transformation
* Saving the processed dataset

---

## 🤖 Machine Learning Models

The following regression algorithms were implemented and compared:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor

---

## 📈 Model Evaluation

Each model was evaluated using standard regression metrics such as:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

The models were compared to identify the best-performing algorithm for bike rental prediction.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Pickle

---

## 📌 Key Highlights

* Comprehensive Exploratory Data Analysis
* Data preprocessing and feature engineering
* Multiple regression algorithms
* Performance comparison across models
* Reproducible machine learning workflow

---

## 👨‍💻 Author

**Tanudip Ghosh**

---

## ⭐ If you found this project helpful, consider giving it a Star!
