# 📊 IBM HR Analytics: Employee Attrition & Performance

This repository contains an end-to-end data analysis and machine learning project to predict employee attrition using IBM HR Analytics data. It covers the complete workflow from EDA to model building and feature importance visualization.

## ❓ Problem Statement

Organizations often struggle to understand why employees leave. High attrition affects productivity, team morale, and increases hiring costs. This project aims to identify patterns behind employee turnover and predict future attrition using machine learning.

## 🎯 Project Objectives

- Analyze HR data and uncover key drivers of attrition
- Build a classification model to predict if an employee is likely to leave
- Provide actionable insights for HR departments

## 🧠 What is Employee Attrition?

Employee attrition refers to the gradual reduction of workforce when employees leave voluntarily or involuntarily and are not immediately replaced. Understanding attrition helps companies reduce turnover and improve employee satisfaction.

## 🔍 Approach & Workflow

1. Load and explore the dataset
2. Clean data and handle categorical variables
3. Perform EDA (visualizations)
4. Build and train a Random Forest model
5. Evaluate performance using accuracy and classification report
6. Visualize feature importance

## 📁 Repository Contents

| File Name                             | Description                                         |
|--------------------------------------|-----------------------------------------------------|
| `Employee_Attrition_Final_Spaced.ipynb` | Main analysis notebook with code and plots         |
| `Attrition Count Chart.png`          | Chart of employee attrition distribution            |
| `Distribution of Employees (Age, Gender, Department).png` | Demographic breakdown |
| `Top 10 important Features.png`      | Feature importance bar chart                        |
| `LICENSE`                            | MIT license for open-source usage                   |
| `README.md`                          | This project overview                               |

## 📊 Key Visualizations

### Attrition Count

![Attrition Count](Attrition%20Count%20Chart.png)

### Distribution of Employees (Age, Gender, Department)

![Distribution](Distribution%20of%20Employees%20(Age%2C%20Gender%2C%20Department).png)

### Top 10 Important Features

![Top Features](Top%2010%20important%20Features.png)

## 🧪 Model Used

- **Algorithm**: Random Forest Classifier
- **Accuracy**: ~87% (based on dataset split)
- **Top Features**: Monthly Income, OverTime, Total Working Years, Job Role

## 🚀 Run This Notebook

### ▶️ Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Shaik-Farida/IBM-HR-Analytics-Employee-Attrition-Performance/blob/main/Employee_Attrition_Final_Spaced.ipynb)

## 📚 Dataset Source

- [IBM HR Analytics Attrition Dataset on Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
  
## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 🙌 Contributions

Feel free to fork the repo, open issues, or submit pull requests to improve the analysis or add more models.
