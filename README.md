# 🧠 Synthetic Departmental Employee Data Project

This project simulates real-world data integration challenges by generating synthetic employee datasets across **five departments**: HR, Finance, IT, Marketing, and Operations.

It demonstrates the complete data science pipeline from **data gathering** and **preprocessing** to building and comparing **machine learning** and **deep learning models** for attrition prediction.

---

## 🔹 Project Overview

We generated 5 different datasets from various "sources":

- 📌 **HR** — Simulated Excel data
- 📌 **Finance** — Simulated CSV data
- 📌 **IT** — Simulated SQL-based data
- 📌 **Marketing** — Simulated JSON data
- 📌 **Operations** — Simulated API response

Each dataset contains **1,000 employee records** with fields like:

- `ExperienceYears`, `Salary`, `Age`, `Gender`, `EducationLevel`, `PerformanceScore`, `LastPromotionYears`, `WorkLifeBalance`, `Attrition`

---

## 🔍 Steps in This Project

1️⃣ **Data Generation**  
Simulated datasets representing various formats (CSV, Excel, JSON, SQL, API) for five departments.

2️⃣ **Data Loading & Integration**  
Combined data using `pandas` to simulate real-life data integration tasks.

3️⃣ **Visualization**  
Used `seaborn` and `matplotlib` to create insightful plots:
- Salary distributions
- Attrition by department
- Correlation heatmap
- Scatterplots (experience vs. performance)

4️⃣ **Preprocessing**
- Label encoding
- One-hot encoding
- Feature scaling using `StandardScaler`

5️⃣ **Machine Learning Model**
- Applied `RandomForestClassifier` to predict employee attrition
- Evaluated using accuracy, confusion matrix, and F1-score

6️⃣ **Deep Learning Model**
- Built a simple Keras neural network (Dense layers with dropout)
- Compared performance against ML model

7️⃣ **Final Model Comparison**
- Visualized accuracy and F1-score of both models using bar charts

---

## 💻 Tech Stack

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- TensorFlow / Keras

---

## 📁 Output File

✅ Project notebook: `Synthetic_Department_Employee_Analysis.ipynb`

---

## 🔗 Connect With Me

If you're interested in data science, machine learning, or collaborative projects, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/ezzeldin-ghazal).

