# 🚗 Vehicle Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the selling price of used cars using Machine Learning models.
It includes data cleaning, visualization, feature engineering, and model comparison to find the best performing algorithm.

---

## 🎯 Problem Statement

To build a regression model that can predict the selling price of a vehicle based on features such as:

* Manufacturing year
* Kilometers driven
* Fuel type
* Seller type
* Transmission
* Owner type
* Brand

---

## 📊 Dataset Features

* year – Manufacturing year of the car
* selling_price – Target variable
* km_driven – Total kilometers driven
* fuel – Type of fuel used
* seller_type – Dealer or individual
* transmission – Manual/Automatic
* owner – Number of previous owners
* brand – Extracted from car name

---

## 🔧 Steps Performed

1. Data Cleaning

   * Removed duplicate records
   * Dropped unnecessary columns
2. Exploratory Data Analysis (EDA)

   * Scatter plots
   * Box plots
   * Correlation heatmap
3. Feature Engineering

   * Extracted brand from car name
   * Encoded categorical variables
4. Train-Test Split

   * 70% training data
   * 30% testing data
5. Model Training

   * Linear Regression
   * Decision Tree Regressor
   * Random Forest Regressor

---

## 📈 Model Performance

| Model             | R² Score  | MAE            |
| ----------------- | --------- | -------------- |
| Linear Regression | ~0.53     | ~1.28 lakh     |
| Decision Tree     | ~0.45     | ~1.30 lakh     |
| Random Forest     | **~0.66** | **~1.04 lakh** |

---

## 🧠 Conclusion

Different regression models were compared to understand how they capture patterns in vehicle pricing. Linear Regression was able to model general trends effectively, showing that some relationships in the data are linear. Decision Tree showed lower performance, likely due to overfitting and instability. Random Forest delivered the best results, indicating that ensemble models are better at capturing complex and non-linear relationships between features.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📂 Project File

* `Vehicle_Price_Prediction_ML.ipynb` – Complete notebook with data preprocessing, visualization, and model training.

---

## 👨‍💻 Author

Machine Learning enthusiast building practical projects to strengthen skills in AI/ML and data analysis.
