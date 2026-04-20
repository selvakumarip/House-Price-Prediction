# 🏠 House Price Prediction using Machine Learning

## 📌 Overview

This project builds a machine learning model to predict house prices based on various features such as quality, size, and location-related factors.

The goal is to understand which factors influence house prices and build an accurate predictive model.

---

## 🚀 Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📊 Model Performance

* **Mean Squared Error (MSE):** 879,305,475
* **R² Score:** 0.885

👉 The model explains **88.5% of the variance**, indicating strong predictive performance.

---

## 🔍 Key Insights

* **OverallQual** is the most important feature (~55% importance)
* **GrLivArea (Living Area)** strongly impacts price
* Basement and floor area also contribute significantly
* Garage and lot size have moderate influence

---

## 📈 Visualizations

### Actual vs Predicted Prices

![Actual vs Predicted](images/Actual_Vs_Predicted.png)

### Feature Importance

![Feature Importance](images/Feature_importance.png)

### House Price Prediction

![House Price Prediction](images/House_price_prediction.png)



---

## ⚙️ Project Workflow

1. Data Loading
2. Data Cleaning (handling missing values)
3. Feature Selection
4. Model Training (Linear Regression & Random Forest)
5. Model Evaluation
6. Feature Importance Analysis

---

## 📁 Project Structure

```
House_price_prediction/
│
├── data/
│   └── train.csv
│
├── notebook/
│   └── house_price.ipynb
│
├── images/
│   ├── Actual_vs_Predicted.png
│   └── Feature_importance.png
│   └── House_price_prediction.png
│
├── README.md
├── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Run the notebook:

   ```
   house_price.ipynb
   ```

---

## 🌟 Future Improvements

* Hyperparameter tuning
* Add more advanced models (XGBoost)
* Deploy as a web app
* Improve feature engineering

---

## 👤 Author

Selva Kumari Padmanabhan

---

## ⭐ Acknowledgement

Dataset from Kaggle House Price Competition
