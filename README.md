# Land Price Prediction using Machine Learning

This project predicts the **price of land** based on multiple features such as **area, proximity to city, soil fertility, water source availability, weather conditions, and year** using **Linear Regression** in Python.

---

## 📌 Features
- Preprocessing of categorical variables using **Label Encoding**
- **StandardScaler** for feature scaling
- Model training using **Linear Regression**
- Model evaluation with **R² score** and **RMSE**
- Visualization: **Actual vs Predicted Prices**
- Interactive user input for prediction
- Support for **SI units** (area converted from acres to square meters)
- Output formatting in **Lakhs and Crores (INR)**

---

## 🛠 Tech Stack
- Python 3.x
- Pandas
- Scikit-learn
- NumPy
- Matplotlib

---

## 📂 Dataset
The dataset should be named **`data.csv`** and must contain the following columns:
- `Area` (in acres)
- `Near city` (Yes/No or categorical)
- `Soil fertility` (categorical)
- `Water Source` (categorical)
- `Weather condtion` (categorical)
- `Year` (integer)
- `Price` (in INR)

---

## ⚙ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/land-price-prediction.git
cd land-price-prediction
pip install -r requirements.txt
