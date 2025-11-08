# 🚢 Titanic Survival Prediction — AI-Powered Data Insights  

## 📘 Project Overview  
This project applies machine learning and AI-assisted analysis to predict passenger survival on the Titanic.  
The goal is to demonstrate how modern data analytics tools—like **GitHub Copilot** and **scikit-learn**—can automate data workflows and enhance decision-making accuracy.  

---

## 🔍 Key Techniques  
- **Data Cleaning:** Handling missing values and encoding categorical features  
- **Exploratory Data Analysis (EDA):** Visualizing survival trends by gender, age, and class  
- **Machine Learning:** Logistic Regression model for classification  
- **Model Evaluation:** Accuracy, precision, recall, and F1 score  
- **AI Assistance:** GitHub Copilot suggestions in Visual Studio Code  

---

## 📊 Dataset Summary  
**Source:** Seaborn Titanic dataset  
**Rows:** 891 | **Columns:** 12  
**Target Variable:** `survived` (1 = survived, 0 = did not survive)  

| Feature | Description |
|----------|-------------|
| pclass | Passenger class (1 = First, 3 = Third) |
| sex | Gender of the passenger |
| age | Passenger age in years |
| fare | Ticket price |
| embarked | Port of embarkation |
| survived | Survival status (target variable) |

---

## 📈 Results  
- **Accuracy:** 82%  
- **Precision & Recall:** Balanced performance between false positives/negatives  
- **Key Finding:** Female passengers and those in higher classes had significantly higher survival rates  

---

## 🖼️ Visualization  
Below is a sample chart showing how survival rates vary by gender and passenger class:  

![Survival Rate by Class and Gender](plots/survival_plot.png)  

---

## 🧭 Business Insights  
- Survival odds were linked to **access priority (class)** and **demographics (gender/age)**.  
- Demonstrates how **data-driven decisions** can reduce bias and improve crisis planning.  

---

## 🛠️ Tools & Technologies  
| Category | Tools |
|-----------|--------|
| Programming | Python |
| Libraries | pandas, seaborn, matplotlib, scikit-learn |
| IDE | Visual Studio Code + GitHub Copilot |
| Version Control | Git + GitHub |

---

## 🧩 Next Steps  
- Test ensemble models (**Random Forest**, **XGBoost**)  
- Integrate **SHAP** for model interpretability  
- Deploy the model using **Streamlit** or **FastAPI**  

---

👤 **Author:** Idriss Kargbo  
🔗 **GitHub:** [Ialuma](https://github.com/Ialuma)  
💼 **Google Advanced Data Analytics Capstone Project (Course 7)**  

💡 This project illustrates the synergy between human reasoning and AI-powered assistance in modern data science workflows.  
