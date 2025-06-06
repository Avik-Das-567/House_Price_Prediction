# Linear Regression with Streamlit - House Price Prediction
### App Link
- https://linear-regression-houseprice-prediction.streamlit.app/
---
### What is Linear Regression?
- Linear Regression is a **math method** used to **predict numbers**.
- It draws a **straight line** through data points.
- It helps **understand relationships** between two things.
---
### Required Python Packages
- **`scikit-learn`** - To build machine learning models
- **`streamlit`** - To build data apps
- **`pandas`** - To work with the dataset
---
### Example Problem
- Predicting House Price Based on Area.
- We have data about **Area in Square Feet** and **Price in Thousands**.

| Area\_in\_Sqft | Price\_in\_Thousands |
| -------------- | -------------------- |
| 1000           | 150                  |
| 1200           | 180                  |
| 1500           | 220                  |
| 1800           | 260                  |
| 2000           | 300                  |

---
### How It Works
- Load the data using **`pd.read_csv()`**.
- Train a model using **`LinearRegression()`**.
- Ask for user input using **`st.number_input()`**.
- Show the result using **`st.write()`**.
---
