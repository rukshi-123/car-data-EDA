uriudnieurcijenckjdnc
# car-data-EDA
# 🚗 Car Price Prediction Project

Welcome to the **Car Price Prediction** project! This repository demonstrates the use of machine learning models to predict the selling price of used cars using Python’s data science ecosystem.

---

## 📦 Dataset Overview

The dataset (`car.csv`) contains **301 rows** and these features:

| Feature        | Description                                   |
|----------------|-----------------------------------------------|
| Car_Name       | Name of the car                               |
| Year           | Year of manufacture                           |
| Selling_Price  | Price at which the car was sold (target)      |
| Present_Price  | Current ex-showroom price                     |
| Kms_Driven     | Kilometers driven                             |
| Fuel_Type      | Type of fuel (Petrol/Diesel/CNG)              |
| Seller_Type    | Dealer or Individual                          |
| Transmission   | Transmission type (Manual/Automatic)          |
| Owner          | Number of previous owners                     |

---

## 🛠️ Libraries Used

| Library                | Purpose                                                       |
|------------------------|--------------------------------------------------------------|
| `numpy`                | Efficient array computations                                 |
| `pandas`               | Data manipulation and analysis                               |
| `matplotlib`, `seaborn`| Data visualization                                           |
| `sklearn` (scikit-learn)| ML models, preprocessing, evaluation metrics                |
| `warnings`             | Ignore unnecessary warnings                                  |

---

## 🔎 Data Processing Steps

- **Load Data:** Read CSV into a Pandas DataFrame.
- **Initial Exploration:** Use `.head()` and `.describe()` for a quick overview.
- **Encoding:** Encode categorical columns (`Fuel_Type`, `Seller_Type`, `Transmission`) numerically using `LabelEncoder`.
- **Feature Selection:** Prepare features (X) and target (`Selling_Price`) for modeling.

---


