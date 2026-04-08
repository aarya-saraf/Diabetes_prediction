🧠 Diabetes Prediction using Machine Learning (SVM)
📌 Project Overview

This project predicts whether a person is diabetic or not using a Machine Learning model (Support Vector Machine) trained on the PIMA Diabetes Dataset.

The model analyzes medical attributes like glucose level, BMI, age, etc., and provides a prediction.

🚀 Features
Data preprocessing & analysis
Feature scaling using Standardization
Model training using SVM (Linear Kernel)
Accuracy evaluation
Real-time prediction system
📂 Dataset Information
Dataset: PIMA Diabetes Dataset
Total Records: 768
Features: 8
Target Variable: Outcome
0 → Non-Diabetic
1 → Diabetic
⚙️ Technologies Used
Python 🐍
NumPy
Pandas
Scikit-learn
🔄 Project Workflow
Data Collection → Data Preprocessing → Data Standardization → Train-Test Split 
→ Model Training (SVM) → Model Evaluation → Prediction

🧪 Model Training
Algorithm: Support Vector Machine (SVM)
Kernel: Linear
Train-Test Split: 80:20
📊 Model Performance
Metric	Score
Training Accuracy	78.66%
Testing Accuracy	77.27%
🔮 Prediction System

Example Input:

(5,166,72,19,175,25.8,0.587,51)


Output:

The person is diabetic

🖥️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Project
Open Jupyter Notebook / Google Colab
Run all cells
📁 Project Structure
diabetes-prediction/
│
├── diabetes.csv
├── diabetes_prediction.ipynb
├── requirements.txt
└── README.md

📌 Requirements

Create a requirements.txt file with:

numpy
pandas
scikit-learn

🎯 Future Improvements
Use advanced models (Random Forest, XGBoost)
Deploy as a web app (Flask/Streamlit)
Improve accuracy with hyperparameter tuning
Add UI for user input
