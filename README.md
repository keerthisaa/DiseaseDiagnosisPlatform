# 🩺 Disease Diagnosis Platform

A user-friendly, AI-powered platform that helps in early diagnosis of multiple diseases using machine learning. Built entirely with **Streamlit**, it provides fast and reliable predictions by analyzing user inputs using trained ML models.

---

## 📌 Table of Contents

- [🚀 Overview](#-overview)  
- [🔍 Features](#-features)  
- [🧪 Supported Diseases](#-supported-diseases)  
- [🛠️ Tech Stack](#-tech-stack)  
- [📁 Directory Structure](#-directory-structure)  
- [⚙️ Setup Instructions](#-setup-instructions)  

---

## 🚀 Overview

The **Disease Diagnosis Platform** allows users to input health-related parameters and receive predictions about potential diseases. It integrates multiple ML models into one interactive web interface.

---

## 🔍 Features

- 🔬 Predict multiple diseases using a single interface  
- 🧠 Machine Learning–powered backend  
- 📊 Real-time predictions with result interpretation  
- 🖥️ Streamlit-based intuitive and responsive UI  
- 🛡️ No data is stored; ensures user privacy  
- 📱 Accessible on desktop, tablet, and mobile devices  

---

## 🧪 Supported Diseases

This platform currently supports prediction for:

- ✅ Diabetes  
- ✅ Heart Disease  
- ✅ Parkinson's Disease  
- ✅ Breast Cancer  
- ✅ Chronic Kidney Disease  
- ✅ Liver Disease  
- ✅ Hepatitis  
- ✅ Lung Cancer  

---

## 🛠️ Tech Stack

| Layer       | Technology         |
|-------------|--------------------|
| Frontend    | Streamlit          |
| Backend     | Python, Pandas     |
| ML Models   | Scikit-learn       |
| File Format | Pickle (.pkl)      |
| IDE         | VS Code / Jupyter  |

---

## 📁 Directory Structure

DiseaseDiagnosisPlatform/
│
├── code/
│ ├── init.py
│ ├── DiseaseModel.py
│ ├── helper.py
│ ├── train.py
│ └── data/
│ ├── clean_dataset.tsv
│ ├── dataset.csv
│ ├── lung_cancer.csv
│ ├── symptom_Description.csv
│ ├── symptom_precaution.csv
│ └── Symptom-severity.csv
│
├── disease_prediction_env/ # Virtual environment (optional)
├── models/ # Trained model files (.pkl)
│
├── app.py # Main Streamlit app
├── requirements.txt # Python dependencies
├── data.db # SQLite database (if used)
│
├── assets/ # (Optional) move all images here
│ ├── logo.png
│ ├── heart.jpg
│ ├── liver.jpg
│ ├── lung.jpg
│ ├── negative.jpg
│ ├── positive.jpg
│ ├── d3.jpg
│ ├── h.png
│ ├── j.jpg
│ ├── heart2.jpg
│ └── 63.gif
│
└── README.md

---

## ⚙️ Setup Instructions

### ✅ Prerequisites

- Python 3.8 or above  
- Git installed  
- pip (Python package manager)

---

### 💻 Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/keerthisaa/DiseaseDiagnosisPlatform.git
cd DiseaseDiagnosisPlatform

# 2. Create and activate virtual environment
python -m venv venv

# For Windows
venv\Scripts\activate

# For Linux/Mac
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
