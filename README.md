# 🏠 Delhi House Price Prediction
---

## 📌 Project Overview

The **Delhi House Price Prediction** project aims to build a robust machine learning model capable of accurately estimating residential property prices across different localities in Delhi.

In a rapidly evolving real estate market, pricing is influenced by multiple dynamic factors such as location, area, amenities, and property type. This project leverages historical housing data to uncover these relationships and generate reliable price predictions.

The dataset, sourced from Kaggle, consists of multiple features including structural attributes (area, BHK, bathrooms) and contextual attributes (locality, furnishing status, transaction type). By applying regression-based machine learning techniques, the project provides a data-driven approach to property valuation.

---

## 📊 Data Dictionary

The dataset contains **1259 entries and 11 features**, each contributing to the prediction of house prices.

| Column Name | Description                                    |
| ----------- | ---------------------------------------------- |
| Area        | Size of the property (in square feet)          |
| BHK         | Number of bedrooms                             |
| Bathroom    | Number of bathrooms                            |
| Furnishing  | Furnishing status (Furnished/Semi/Unfurnished) |
| Locality    | Geographic location of the property            |
| Parking     | Number of parking spaces                       |
| Price       | Target variable (Price in INR)                 |
| Status      | Construction status (Ready/Under Construction) |
| Transaction | Type of sale (New/Resale)                      |
| Type        | Property type (Apartment/Builder Floor, etc.)  |
| Per_Sqft    | Price per square foot                          |

---

## 🔍 Exploratory Data Analysis (EDA) Insights

* **Area vs Price:** Strong positive correlation — larger houses command higher prices
* **Locality Impact:** Premium areas such as *Vasant Kunj, Punjabi Bagh, and Lajpat Nagar* show significantly higher pricing trends
* **BHK Influence:** More bedrooms generally lead to higher property valuation
* **Property Preference:** Builder floors and newly constructed properties show higher demand
* **Price Distribution:** Skewed distribution indicating presence of high-value luxury properties

---

## 🤖 Model Development

The project utilizes supervised learning techniques for regression:

* **Decision Tree Regressor**
* **Random Forest Regressor**

### ⚙️ Steps Involved:

* Data Cleaning & Handling Missing Values
* Encoding Categorical Variables
* Feature Selection
* Model Training & Testing
* Performance Evaluation

---

## 📈 Model Performance

* **Random Forest Regressor Accuracy:** **~84.98%** ✅
* Outperformed Decision Tree due to better generalization and reduced overfitting

---

## 🧠 Conclusion

This project successfully demonstrates how machine learning can be applied to solve real-world pricing problems in the real estate domain. By leveraging structured data and regression models, it provides a scalable and data-driven solution for estimating house prices with high reliability.

---
