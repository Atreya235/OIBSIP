# 🚗 Car Price Prediction using Machine Learning

This project predicts the **selling price of a car** based on various features using a **Random Forest Regressor** model. It allows user input and provides an accurate price estimate of used cars based on their attributes.

---

## 🔍 Problem Statement

The price of a car depends on various factors such as:

- Goodwill of the car brand
- Fuel type
- Number of previous owners
- Present price and mileage
- Transmission type and car age

This project aims to develop a machine learning model that can accurately predict the **resale value** of a car.

---

## 📁 Dataset Features

| Feature Name     | Description |
|------------------|-------------|
| Car_Name         | Name of the car (removed during preprocessing) |
| Year             | Year of manufacturing |
| Selling_Price    | Target variable (price the car is sold at) |
| Present_Price    | Current ex-showroom price |
| Kms_Driven       | Distance driven |
| Fuel_Type        | Type of fuel (Petrol/Diesel/CNG) |
| Seller_Type      | Dealer or Individual |
| Transmission     | Manual or Automatic |
| Owner            | Number of previous owners |

---

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Seaborn & Matplotlib (for visualization)
- Scikit-learn (Random Forest Regressor)

---

## 🧠 Model Used

- **RandomForestRegressor**
- Evaluation Metric: **R² Score**

---

## 📊 Visualizations Included

- Histogram of Selling Prices
- Scatter Plot: Present Price vs Selling Price
- Heatmap: Feature Correlations
- Residual Error Distribution

---

## 🚀 How to Run the Project

### Step 1️⃣: Clone or Download

```bash
git clone https://github.com/yourusername/car-price-prediction.git
cd car-price-prediction
