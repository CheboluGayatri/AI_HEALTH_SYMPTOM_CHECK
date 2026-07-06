# 🩺 AI Health Symptom Checker using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_Framework-black?style=for-the-badge&logo=flask)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Scikit--Learn-orange?style=for-the-badge)
![SQLite](https://img.shields.io/badge/Database-SQLite-003B57?style=for-the-badge&logo=sqlite)
![License](https://img.shields.io/badge/Academic_Project-Final_Year-success?style=for-the-badge)

### AI-Powered Medical Symptom Prediction & Clinical Report Generation

*A production-ready Final Year Major Project built using Machine Learning, Flask, and Modern Web Technologies.*

### 🌐 Live Demo
**🔗 Application:** https://ai-health-symptom-check.onrender.com/

### 💻 GitHub Repository
**🔗 Repository:** https://github.com/CheboluGayatri/AI_HEALTH_SYMPTOM_CHECK

</div>

---

# 📖 Overview

The **AI Health Symptom Checker** is an intelligent healthcare web application that predicts possible diseases based on user-selected symptoms using **Machine Learning**.

Unlike traditional symptom checkers that rely on manually written rules, this project uses a **Random Forest Classifier** trained on a medical symptom dataset to provide probability-based disease predictions.

The application also includes:

- 🔐 Secure User Authentication
- 🤖 AI Medical Chatbot
- 🎤 Voice-based Symptom Selection
- 📄 PDF Clinical Report Generation
- 📊 Interactive Prediction Charts
- 🌙 Dark/Light Theme
- 📱 Responsive User Interface

This project demonstrates the practical integration of **Artificial Intelligence, Machine Learning, Web Development, Data Science, and Database Management** into a healthcare solution.

---

# 🚀 Live Application

| Platform | Link |
|----------|------|
| 🌐 Live Demo | https://ai-health-symptom-check.onrender.com |
| 💻 GitHub Repository | https://github.com/CheboluGayatri/AI_HEALTH_SYMPTOM_CHECK |

---

# ✨ Features

## 🧠 Machine Learning Disease Prediction

- Random Forest Classification
- Top-3 probable disease predictions
- Probability percentage for each prediction
- Dynamic feature extraction
- Zero hardcoded symptom mapping
- Dataset-driven prediction pipeline

---

## 🎤 Voice-Based Symptom Recognition

- Browser microphone support
- Web Speech API integration
- Automatic symptom checkbox selection
- Hands-free interaction
- Real-time speech processing

---

## 🤖 AI Medical Chatbot

- Hugging Face Inference API integration
- Health guidance
- Medication suggestions
- Preventive recommendations
- Offline fallback chatbot

---

## 📄 PDF Clinical Report Generator

Generate professional downloadable reports containing:

- Patient details
- Selected symptoms
- Predicted diseases
- Probability analysis
- Clinical recommendations
- Date & Time
- Medical disclaimer
- Probability charts

---

## 📊 Visualization Dashboard

Automatic generation of:

- Disease probability pie chart
- Confidence bar chart
- Matplotlib visualizations
- PDF embedded graphics

---

## 🔐 Authentication System

- User Registration
- Login
- Password Hashing
- Session Management
- Flask-Login integration
- Secure Authentication

---

## 💾 Database Management

SQLite Database stores:

- User Accounts
- Login Credentials
- Assessment History
- Generated Reports
- Disease Predictions

---

## 🌙 Modern UI

- Bootstrap 5
- Dark Mode
- Light Mode
- Responsive Design
- Mobile Friendly
- Clean Healthcare Interface

---

# 🛠 Tech Stack

## Programming Languages

- Python
- HTML5
- CSS3
- JavaScript

---

## Backend

- Flask
- Flask-Login

---

## Frontend

- HTML5
- CSS3
- Bootstrap 5
- JavaScript

---

## Machine Learning

- Scikit-learn
- Random Forest Classifier

---

## Data Processing

- Pandas
- NumPy

---

## AI

- Hugging Face Transformers API

---

## Database

- SQLite

---

## Data Visualization

- Matplotlib
- Seaborn

---

## Voice Recognition

- SpeechRecognition
- Web Speech API

---

## PDF Generation

- ReportLab

---

# 📂 Project Structure

```
AI_Health_Symptom_Checker/
│
├── app.py
├── auth.py
├── chatbot.py
├── database.py
├── report_generator.py
├── symptom_checker.py
├── visualizations.py
├── voice_input.py
├── dataset.csv
├── requirements.txt
├── README.md
│
├── instance/
│   └── users.db
│
├── reports/
│
├── static/
│   ├── css/
│   ├── js/
│   └── charts/
│
└── templates/
    ├── dashboard.html
    ├── login.html
    ├── register.html
    ├── report.html
    └── chatbot.html
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/CheboluGayatri/AI_HEALTH_SYMPTOM_CHECK.git
```

```bash
cd AI_HEALTH_SYMPTOM_CHECK
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv
```

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Configure Environment Variable

Windows

```bash
set HF_API_TOKEN=your_token
```

Linux/macOS

```bash
export HF_API_TOKEN=your_token
```

---

## Run Application

```bash
python app.py
```

Visit

```
http://localhost:5000
```

---

# 🧠 Machine Learning Workflow

```
Medical Dataset
       │
       ▼
Feature Extraction
       │
       ▼
Label Encoding
       │
       ▼
Random Forest Training
       │
       ▼
Prediction
       │
       ▼
Top-3 Disease Results
       │
       ▼
Probability Analysis
       │
       ▼
PDF Report Generation
```

---

# 📊 ML Pipeline

### Dataset Loading

- Reads dataset.csv
- Automatically detects symptom columns

### Feature Engineering

- Binary symptom vectors
- Dynamic preprocessing

### Model Training

- Random Forest Classifier
- 100 Decision Trees

### Prediction

- Predicts disease
- Calculates confidence score
- Returns Top-3 probable diseases

---

# 🗄 Database Schema

## users

| Field | Description |
|--------|-------------|
| id | Primary Key |
| username | Username |
| email | Unique Email |
| password | Hashed Password |

---

## diagnostic_reports

| Field | Description |
|--------|-------------|
| report_id | Primary Key |
| user_id | Foreign Key |
| symptoms | Selected Symptoms |
| prediction | Predicted Disease |
| confidence | Prediction Score |
| timestamp | Assessment Date |

---

# 📄 Generated Report Includes

- Patient Details
- Symptoms
- Disease Prediction
- Top-3 Predictions
- Probability Analysis
- Pie Chart
- Bar Chart
- Medical Recommendations
- Date & Time
- Medical Disclaimer

---

# 🔒 Security Features

- Password Hashing
- Secure Login
- Flask Sessions
- Protected Routes
- SQL Injection Protection
- Authentication Middleware

---

# 📸 Application Modules

- Login System
- Registration System
- Dashboard
- Symptom Checker
- Voice Recognition
- Disease Prediction
- AI Chatbot
- PDF Report Generator
- History Management

---

# 📈 Future Enhancements

The current application is built using **Python Flask**.

The next enterprise version will include a modern full-stack architecture powered by Artificial Intelligence.

### Planned Technology Stack

- ⚛ React.js
- 🟢 Node.js
- 🚀 Express.js
- 🍃 MongoDB
- 🔥 JWT Authentication
- 🤖 Advanced LLM-based Medical Assistant
- 📱 Progressive Web App (PWA)
- ☁ Cloud Database
- 📊 Advanced Analytics Dashboard
- 📅 Appointment Booking
- 💬 Real-time Chat
- 📹 Video Consultation
- 🩺 Wearable Device Integration
- 🔔 Smart Notifications
- 🌍 Multi-language Support
- 📲 Android & iOS Mobile Application
- ☁ Docker Deployment
- ☸ Kubernetes Support
- 🔄 CI/CD Pipeline
- 📡 REST API
- 📈 Admin Dashboard
- 📤 Email Notifications
- 📥 Medical History Export
- 🧬 Personalized Health Recommendations

---

# 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Machine Learning
- Artificial Intelligence
- Healthcare Informatics
- Flask Development
- Database Management
- Authentication Systems
- REST Architecture
- Speech Recognition
- Data Visualization
- PDF Generation
- Responsive UI Design

---

# ⚠ Medical Disclaimer

> This application is developed **strictly for educational and academic purposes**.

The predictions generated by the Machine Learning model are based on symptom patterns and **should not be considered professional medical advice, diagnosis, or treatment**.

Always consult a qualified healthcare professional for accurate diagnosis and emergency medical conditions.

---

# 👩‍💻 Developer

**Gayatri Chebolu**

### Connect With Me

- 💻 GitHub: https://github.com/CheboluGayatri
- 🌐 Project Repository: https://github.com/CheboluGayatri/AI_HEALTH_SYMPTOM_CHECK
- 🚀 Live Application: https://ai-health-symptom-check.onrender.com

---

# ⭐ Support

If you found this project helpful:

⭐ Star the repository

🍴 Fork the project

💡 Share your suggestions

📩 Open an Issue

---

<div align="center">

### Made with ❤️ using Python, Flask, Machine Learning & AI

**AI Health Symptom Checker**

*Empowering Healthcare with Artificial Intelligence.*

</div>
