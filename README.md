# Customer-Churn-Prediction

# 📊 Customer Churn Prediction Web App

A Machine Learning based web application that predicts whether a customer is likely to **churn (leave the service)** or not.  
This project uses a trained ML model and is deployed using **FastAPI**.

---

## 🚀 Features
- Predicts customer churn using Machine Learning
- FastAPI backend
- Interactive API testing using Swagger UI
- Pre-trained model with encoders and scaler
- Easy to run locally

---

## 🧠 Machine Learning Details
- Model trained using historical customer data
- Data preprocessing includes:
  - Label Encoding
  - Standard Scaling
- Output:
  - Churn / No Churn prediction
  - Probability score

---

## 🛠️ Tech Stack
- **Python**
- **FastAPI**
- **Uvicorn**
- **Scikit-learn**
- **NumPy**
- **Pandas**

---

## 📁 Project Structure
customer churn/
│
├── fastapi_app.py # FastAPI application
├── model.pkl # Trained ML model
├── scaler.pkl # StandardScaler
├── encoders.pkl # Label Encoders
├── requirements.txt
└── README.md


---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone <your-github-repo-link>
cd customer-churn

# 🌐 Access the App

## Open your browser and go to:

http://127.0.0.1:8000/docs
Use the /predict endpoint to test the churn prediction.

# 📌 API Endpoint
POST /predict

Takes customer details as input and returns:

Churn prediction

Probability score

# 🎯 Use Cases

Telecom customer retention analysis

Subscription-based business insights

Churn risk identification

# 📚 Learning Outcomes

Building ML-powered APIs

Model deployment using FastAPI

Handling encoders and scalers

API testing with Swagger UI

# 👩‍💻 Author

Arpita Bagdawat
B.Tech (AI & Data Science)
📍 Ujjain, India

🔗 LinkedIn: https://www.linkedin.com/in/arpita-b-66a996292
