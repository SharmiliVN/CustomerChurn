# 📊 Customer Churn Prediction App — Streamlit + Machine Learning

A Machine Learning web application that predicts whether a customer is likely to churn based on user inputs. Built using a trained model and deployed with Streamlit.

---

## 🚀 Features

- Predicts customer churn (Yes / No)  
- Interactive UI using Streamlit  
- Uses trained model (`model.pkl`)  
- Applies scaling using `scaler.pkl`  
- Real-time predictions  

---

## 📥 Input Features

- Age  
- Gender (Male = 0, Female = 1)  
- Tenure  
- Monthly Charges  

---

## ⚙️ How It Works

1. User enters input values  
2. Gender is encoded  
3. Data is scaled using scaler  
4. Model predicts churn  
5. Result is displayed  

---

## 🛠️ Tech Stack

- Python  
- Streamlit  
- scikit-learn  
- NumPy  
- joblib  

---

## 📂 Project Structure

app.py → Streamlit app  
model.pkl → Trained model  
scaler.pkl → Feature scaler  
README.md → Documentation  

---

## ▶️ Run Locally

### 1. Install dependencies
pip install streamlit scikit-learn numpy joblib

### 2. Run the app
streamlit run app.py

---

## 📈 Output

- **Yes** → Customer likely to churn  
- **No** → Customer likely to stay  

---

## ⚠️ Notes

- Keep `model.pkl` and `scaler.pkl` in the same folder  
- Input order must be:  
  Age, Gender, Tenure, MonthlyCharges  

---

## 🌟 Highlights

- End-to-end ML deployment project  
- Real-time prediction  
- Clean UI + ML integration  

---

⭐ If you found this useful, give it a star!
