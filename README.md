# 💼 Employee Salary Prediction using Machine Learning

This project aims to build a machine learning model that accurately predicts employee salaries based on features like experience, education, job role, department, location, and performance. It was developed as part of the IBM SkillsBuild AICTE Batch 2 (2025-26) Capstone Project.

## 📌 Problem Statement

Accurate salary prediction is important for maintaining fairness, transparency, and budgeting in organizations. Manual estimation methods are often error-prone and time-consuming. Our goal is to automate and improve this process using machine learning techniques.

## 🚀 Technologies Used

- **Language**: Python 3.x  
- **IDE/Platform**: Jupyter Notebook, Google Colab  
- **Web App Deployment**: Streamlit  
- **Version Control**: GitHub  

## 📦 Libraries

- `pandas`, `numpy` – Data handling  
- `matplotlib`, `seaborn` – Visualization  
- `scikit-learn` – Machine Learning  
- `streamlit` – Web App Interface

## 📁 Dataset

A custom dataset was created with the following fields:
- `Experience`
- `Qualification`
- `Job Role`
- `Gender`
- `Department`
- `Location`
- `Salary`

## 🧠 ML Approach

1. Load and inspect the dataset  
2. Remove outliers using 95th percentile filtering  
3. Encode categorical variables using `LabelEncoder`  
4. Split data (80% training, 20% testing)  
5. Train model using **Random Forest Regressor**  
6. Evaluate with R² Score and MSE  
7. Build prediction interface using Streamlit  
8. Host on GitHub

## 📊 Results

- Achieved R² Score: **~0.88**  
- Outlier handling improved prediction accuracy  
- Final model tested on new inputs via UI  
- Deployed Streamlit app for real-time prediction

## 🌐 GitHub Pages

👉 [GitHub Repository Link](https://github.com/varaprasadvp/employee-salary-prediction-using-ML-algorithms)

## 🎯 Future Scope

- Integrate with real HRMS platforms  
- Use deep learning for better accuracy  
- Expand dataset using Kaggle or live HR data  
- Add more features like skills, certifications, and performance history

## 🙋 Author

**Sunkeswarapu Venkata Varaprasad**  
B.Tech, Artificial Intelligence  
QIS College of Engineering and Technology  
📧 varaprasadvaraprasad196@gmail.com

## 🏆 Project Under

🎓 IBM SkillsBuild – AICTE Batch 2 (2025-26)

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)  
- [Pandas Documentation](https://pandas.pydata.org/docs/)  
- [Streamlit Docs](https://docs.streamlit.io/)  
- [IBM SkillsBuild Platform](https://skillsbuild.org)

