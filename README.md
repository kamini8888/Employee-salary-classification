# 💼 Employee Salary Classification App

This is a Streamlit-based web application that predicts whether an employee earns **>50K** or **≤50K** annually based on user inputs such as age, education level, occupation, working hours per week, and other demographic features.

---

## 📌 Project Overview

The app utilizes a machine learning model trained on the **UCI Adult Census dataset** to classify employee salary classes. The solution includes:

- 📊 **Real-time prediction interface** using Streamlit  
- 📁 **Batch prediction** support with CSV file uploads  
- ✅ **Sidebar-based input form** for easy user interaction  
- 💾 Best-performing model (**Gradient Boosting**) saved with `joblib`  
- 🌐 Online deployment capability using **Pyngrok**

---

## ⚙️ Features

- **Input Fields**: Age, Workclass, Education Level (numeric), Marital Status, Occupation, Relationship, Race, Gender, Capital Gain/Loss, Hours per Week, Native Country  
- **Model Used**: Multiple algorithms tested; **Gradient Boosting** selected based on performance  
- **Deployment**: Ready to deploy using **Streamlit** and **Ngrok**

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/employee-salary-classification.git
cd employee-salary-classification
