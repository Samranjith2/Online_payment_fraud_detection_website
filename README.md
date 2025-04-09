# 💳 Online Payment Fraud Detection Website

This project is a web-based application designed to detect fraudulent online payment transactions using machine learning techniques. It offers a user-friendly interface where users can input transaction details and receive real-time predictions about the legitimacy of the transaction.

## 🔍 Features

- 🔐 Fraud Detection using trained machine learning models
- 🌐 Web interface built with Streamlit
- 📊 Visualizations of transaction patterns
- 📁 Upload CSV files for bulk predictions
- 💡 Real-time feedback on model predictions

## 🧠 Machine Learning Model

The model is trained on a dataset of online payment transactions. It uses various features such as transaction amount, location, time, and user history to detect fraudulent behavior.

### Techniques Used:
- Data Preprocessing & Cleaning
- Feature Selection
- Classification Algorithms (e.g., Logistic Regression, Random Forest, XGBoost)
- Model Evaluation Metrics (Accuracy, Precision, Recall, F1-Score)

## 🛠️ Tech Stack

- Python 🐍
- Streamlit 🌐
- Pandas & NumPy 📊
- Scikit-learn 🤖
- Matplotlib & Seaborn 📈

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Samranjith2/Online_payment_fraud_detection_website.git
   cd Online_payment_fraud_detection_website

2.Install the required packages It's recommended to use a virtual environment.

pip install -r requirements.txt

3.Run the Streamlit app

streamlit run app.py

4.Access the web app

Open your browser and go to: http://localhost:8501

##📂 Project Structure

Online_payment_fraud_detection_website/
│
├── app.py                      # Streamlit web app
├── fraud_detection_model.pkl   # Trained ML model
├── preprocessing.py            # Data preprocessing script
├── utils.py                    # Utility functions
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation

##📊 Dataset
The dataset used for this project includes anonymized records of online payment transactions. Each record contains:

Transaction ID

Transaction Amount

Timestamp

Location

User ID

Class Label (Fraud/Not Fraud)

   
