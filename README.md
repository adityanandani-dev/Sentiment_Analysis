# 📊 Sentiment Analysis Web App

A Flask-based web application for performing **Sentiment Analysis** on text or CSV files.  
It supports **single text prediction** and **bulk predictions via CSV upload**.  

---

## 🚀 Features
- 🔍 Predict sentiment (`Positive` / `Negative`) from a single text input.  
- 📂 Upload a CSV file for **bulk sentiment prediction**.  
- 📈 Generates a **sentiment distribution pie chart** for bulk predictions.  
- ⚡ Pre-trained **XGBoost model** with CountVectorizer + Scaler preprocessing.  
- 🎨 Simple web interface built using Flask + HTML templates.  

---

## 🛠️ Tech Stack
- **Python 3.x**
- **Flask**
- **Pandas / Numpy**
- **NLTK** (stopwords + PorterStemmer)
- **Matplotlib** (for graph visualization)
- **Scikit-learn** (for preprocessing)
- **XGBoost** (for classification)

---

## 📂 Project Structure
Sentiment-Analysis/
│
├── Models/ # Pre-trained ML models
│ ├── model_xgb.pkl
│ ├── scaler.pkl
│ └── countVectorizer.pkl
│
├── templates/ # HTML templates
│ └── landing.html
│
├── app.py # Flask application
├── requirements.txt # Dependencies
└── README.md # Project documentation
