# 🧠 Student Stress Detection - Flask Backend

This repository contains the backend of the **Student Stress Detection** project, built using **Flask** and powered by a **Random Forest classifier**. It provides RESTful APIs to predict student stress levels based on structured inputs like academic workload, sleep patterns, social factors, and more.

---

## 🎯 Objective

The project aims to assist institutions and students in identifying stress levels early using data-driven insights and machine learning models.

---

## 🛠️ Tech Stack

| Component   | Technology         |
|-------------|--------------------|
| Backend     | Python (Flask)     |
| ML Model    | Random Forest (scikit-learn) |
| API Format  | RESTful (JSON)     |
| Input Data  | Survey responses, behavioral metrics |
| Deployment  | Flask server (local or cloud) |

---

## 📁 Project Structure

student-stress-detection/
├── app.py # Main Flask app
├── model.pkl # Trained Random Forest model
├── preprocess.py # Data preprocessing logic
├── requirements.txt # Python dependencies
├── utils.py # Helper functions
└── README.md # This file


---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/zaim03767/student-stress-detection.git
cd student-stress-detection

python -m venv venv
venv\Scripts\activate  # On Windows
# source venv/bin/activate  # On Linux/Mac

pip install -r requirements.txt

python app.py
