# 📊 DiscountMate – Supermarket Price Prediction Using Prophet

**DiscountMate** is a time-series forecasting project that predicts future prices of supermarket products using the [Facebook Prophet](https://facebook.github.io/prophet/) model. The goal is to help customers make smarter shopping decisions by identifying the best time and place to buy products.

---

## 💡 Project Motivation

With rising living costs, predicting when and where discounts occur can empower shoppers to save money. This project was inspired by the need for an accessible, data-driven tool to help communities make informed spending choices.

---

## 🛠️ Technologies Used

- Python
- Facebook Prophet
- Pandas, NumPy
- Matplotlib, Seaborn
- Git/GitHub

---

## 📁 Dataset

The dataset includes historical product prices from various supermarket chains. Features include:
- `Category` – Transaction date
- `Product_Name`
- `Brand`
- `unit-price_x`

---

## 🔍 Key Steps

1. **Data Preprocessing**
   - Handled missing values
   - Removed outliers using IQR
   - Applied log transformations

2. **Feature Engineering**
   - Included `seasonality`, `holiday effects`, and `weekly/monthly trends`

3. **Modeling**
   - Implemented Facebook Prophet model
   - Tuned hyperparameters for trend and seasonality

4. **Evaluation**
   - Model performance:
     - MSE: **0.86**
     - RMSE: **0.93**
     - MAE: **0.74**

5. **Insights**
   - Identified which supermarkets offer the highest discount frequency
   - Forecasted future price trends for specific products

---

## 📈 Results

The model accurately forecasts future prices with 15% improved precision over basic models. Key insights were visualized to aid both businesses and customers in decision-making.

---

## 👩‍💻 Author

**Neha Anil**  
Master of Applied AI – Deakin University  
[LinkedIn](https://www.linkedin.com/in/neha-anil) | [GitHub](https://github.com/nehaanil12345)

---

## 🚀 Future Improvements

- Deploy model as a web dashboard using Streamlit
- Incorporate more features like location, promotions, and store type
- Explore XGBoost and ARIMA for model comparison
