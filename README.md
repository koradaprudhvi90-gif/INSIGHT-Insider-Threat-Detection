# INSIGHT-Insider-Threat-Detection
AI-powered behavioral analytics system to detect insider threats through micro-deviation modeling.
# 🚀 INSIGHT – Intelligent Insider Threat Detection System

INSIGHT is an AI-driven behavioral analytics system designed to detect insider threats by identifying subtle deviations in user activity patterns before malicious actions occur.

---

## 🔍 Problem Statement

Traditional security systems focus on perimeter defense and large anomalies. Insider threats often hide within normal behavior, making them difficult to detect early.

INSIGHT addresses this by analyzing micro-behavioral shifts in:
- Login timings
- File access frequency
- Application usage patterns
- Privilege escalation attempts

---

## 💡 Solution Overview

INSIGHT builds a behavioral baseline for each user and continuously monitors for subtle deviations using machine learning models.

When risk thresholds are crossed, the system alerts the security team with a dynamic risk score.

---

## 🏗 System Architecture

Data Sources → Log Processing → Feature Engineering → AI Model → Risk Scoring → Alert Dashboard

---

## ✨ Key Features

- Behavioral Baseline Modeling
- Micro-Deviation Detection
- Dynamic Risk Scoring
- Real-Time Alerts
- SOC Dashboard
- Department Risk Heatmap
- Continuous Learning Model

---

## 🛠 Tech Stack

### Backend
- Python
- FastAPI
- Scikit-learn
- TensorFlow / PyTorch
- PostgreSQL

### Frontend
- React.js
- Chart.js
- Tailwind CSS

### DevOps
- Docker
- Kubernetes

---

## ⚙ How It Works

1. Collect user activity logs
2. Extract behavioral features
3. Train anomaly detection model
4. Calculate risk score
5. Trigger alerts if threshold exceeded

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/INSIGHT-Insider-Threat-Detection.git
cd INSIGHT-Insider-Threat-Detection
```

### Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 📊 Sample Risk Score Logic

Risk Score =  
(Deviation in login time × weight) +  
(Abnormal file access × weight) +  
(App usage shift × weight)

If Risk Score > Threshold → Alert Triggered

---

## 🎯 Future Improvements

- Integration with SIEM tools
- NLP-based email sentiment analysis
- Role-based adaptive thresholding
- Graph neural networks for behavior correlation

---

## 📈 Impact

INSIGHT shifts cybersecurity from reactive to predictive, enabling organizations to detect insider intent before damage occurs.

---

## 👥 Team

Team Name: SentinelAI  
Team Leader: Prudhvi  

---

## 📜 License

MIT License
