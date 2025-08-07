🩺 Disease Diagnosis Platform
A user-friendly, AI-powered platform that helps in early diagnosis of multiple diseases using machine learning. Built entirely with Streamlit, it provides fast and reliable predictions by analyzing user inputs using trained ML models.

📌 Table of Contents
Overview

Features

Supported Diseases

Tech Stack

Directory Structure

Setup Instructions

Usage

Contributing

License

🚀 Overview
The Disease Diagnosis Platform allows users to input health-related parameters and receive predictions about potential diseases. It integrates multiple ML models into one interactive web interface.

🔍 Features
🔬 Predict multiple diseases using a single interface

🧠 Machine Learning–powered backend

📊 Real-time predictions with result interpretation

🖥️ Streamlit-based intuitive and responsive UI

🛡️ No data is stored; ensures privacy

📱 Accessible on desktop, tablet, and mobile

🧪 Supported Diseases
Currently supports predictions for:

✅ Diabetes

✅ Heart Disease

✅ Parkinson's Disease

✅ Breast Cancer

✅ Chronic Kidney Disease

✅ Liver Disease

✅ Hepatitis

✅ Lung Cancer

🛠️ Tech Stack
Layer	Technology
Frontend	Streamlit
Backend	Python, Pandas
ML Models	Scikit-learn
File Format	Pickle (.pkl)
IDE	VS Code / Jupyter

📁 Directory Structure
bash
Copy
Edit
DiseaseDiagnosisPlatform/
│
├── code/
│   ├── __init__.py
│   ├── DiseaseModel.py
│   ├── helper.py
│   ├── train.py
│   └── data/
│       ├── clean_dataset.tsv
│       ├── dataset.csv
│       ├── lung_cancer.csv
│       ├── symptom_Description.csv
│       ├── symptom_precaution.csv
│       └── Symptom-severity.csv
│
├── models/                  # Trained model files (.pkl)
├── disease_prediction_env/ # Virtual environment (optional)
├── app.py                  # Streamlit frontend file
├── data.db                 # Database if used
├── *.jpg / *.png / *.gif   # Image files for UI
├── requirements.txt        # Required Python packages
└── README.md               # Project documentation
⚙️ Setup Instructions
✅ Prerequisites
Python 3.8 or above

Git installed

pip (Python package manager)

💻 Installation Steps
bash
Copy
Edit
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
▶️ Usage
The web app will open in your browser.

Enter the required medical parameters.

View instant prediction results and interpretation.

Models are pre-trained; no retraining needed for basic use.


Open a Pull Request

