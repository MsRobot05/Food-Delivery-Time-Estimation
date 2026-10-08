
#🚀 AI Delivery Intelligence System

### Predict. Analyze. Optimize.

📸 Application Preview
<img width="1917" height="988" alt="image" src="https://github.com/user-attachments/assets/1af04466-6f0a-4530-88a0-2d6313a6b0c5" />

<img width="1886" height="928" alt="image" src="https://github.com/user-attachments/assets/89f01ea3-bc8f-406c-b8b1-ba5173ac5eb5" />

<img width="1900" height="687" alt="image" src="https://github.com/user-attachments/assets/7d8f9c06-29e8-4360-915d-c224df9eabd8" />

<img width="1894" height="804" alt="image" src="https://github.com/user-attachments/assets/5d24e64e-76ad-4d8b-86a5-a4ce91bfae71" />






## 📌 Project Overview

This project is not just a delivery time predictor.

It is an **AI-powered Operational Decision Support System** designed to:

* Predict food delivery ETA
* Estimate delay risk
* Simulate real-world conditions (traffic, peak hour, weather)
* Provide actionable recommendations

The goal is to improve delivery efficiency and reduce late orders through data-driven insights.

---

## 🎯 Business Problem

Food delivery platforms struggle with:

* Inaccurate ETA predictions
* Late deliveries
* Poor rider allocation
* Customer dissatisfaction

Even small ETA errors can significantly impact:

* Customer trust
* Order cancellation rate
* Platform ratings
* Operational cost

This system helps solve that by predicting ETA and identifying operational risk in advance.

---

## 🧠 System Capabilities

### 1️⃣ ETA Prediction

Predicts delivery time based on:

* Delivery partner age
* Delivery partner rating
* Distance between restaurant and customer
* Order type
* Vehicle type

---

### 2️⃣ Risk Analysis Engine

Classifies delivery into:

* ✅ Low Delay Risk
* ⚠ Moderate Delay Risk
* 🚦 High Delay Risk

Provides a risk score percentage to support operational decisions.

---

### 3️⃣ Real-World Simulation Layer

The system includes simulated operational factors such as:

* Peak hour multiplier
* Traffic congestion level
* Weather impact

This demonstrates how external factors affect delivery time.

---

### 4️⃣ Decision Recommendation Engine

Instead of only predicting time, the system provides:

* Reassignment suggestions
* Surge incentive suggestion
* Risk alerts for long-distance orders
* Operational flagging for low-rated riders

This moves the project from prediction to business intelligence.

---

## 🔬 Machine Learning Approach

### Data Processing

* Cleaned unrealistic age and rating values
* Calculated distance using Haversine formula
* Encoded categorical variables
* Feature engineering (distance bucket, experience score)

### Models Tested

* Linear Regression
* Decision Tree
* Random Forest
* Gradient Boosting

### Optimization 

* Hyperparameter tuning using GridSearchCV
* Cross-validation for stability

### Final Model

Gradient Boosting Regressor selected based on:

* Lowest MAE
* Stable R² score
* Balanced bias-variance performance

---

## 📊 Model Performance

(Replace with your actual numbers)

* MAE: ~3–5 minutes
* RMSE: Stable across folds
* R² Score: 0.70+
* Cross-validation MAE: Consistent

---

## 🖥️ Web Application Features

The Streamlit application includes:

* Interactive user input controls
* Real-time ETA prediction
* Dynamic gauge visualization
* Risk score display
* Feature importance visualization
* Clean dashboard layout

---

## 🛠️ Tech Stack

* Python
* Pandas & NumPy
* Scikit-learn
* Plotly
* Streamlit
* Git



## ▶️ How To Run Locally

1️⃣ Clone repository:

```
git clone https://github.com/yourusername/AI-Delivery-Intelligence-System.git
cd AI-Delivery-Intelligence-System
```

2️⃣ Install dependencies:

```
pip install -r requirements.txt
```

3️⃣ Run application:

```
streamlit run app.py
```

Open in browser:

```
http://localhost:8501
```

---

## 🚀 Future Improvements

* Real-time traffic API integration
* Weather API integration
* REST API deployment using FastAPI
* Model monitoring & logging
* Cloud deployment
* A/B testing simulation

---

## 💡 Key Learning Outcomes

* End-to-end ML pipeline implementation
* Feature engineering for operational systems
* Hyperparameter tuning
* Risk modeling
* Interactive ML deployment
* Version control & iterative development

---

## Acknowledgements

Conceived together with Shweta Pi, who also contributed the presentation. Implementation (data processing, modeling, Streamlit app) by Ani.

## Author

Built by Ani (Shrestha Sengupta), MIT-WPU, Pune.
[GitHub: MsRobot05](https://github.com/MsRobot05)


