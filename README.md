# 🏥 Healthcare Patient Readmission Analysis & Dashboard

## 📌 Project Overview

This project focuses on analyzing patient readmission data from hospitals to identify patterns and risk factors contributing to readmissions.

It includes:

* Data cleaning & preprocessing (Python)
* Feature engineering
* Machine learning model (Logistic Regression)
* Interactive dashboard (Power BI)

---

## 🎯 Objectives

* Predict patient readmission (0 = No, 1 = Yes)
* Identify high-risk patient groups
* Build an interactive dashboard for business insights

---

## 🗂️ Dataset

* Source: Diabetes dataset (130 US hospitals)
* Records: ~100K patient encounters
* Features include:

  * Age group
  * Gender
  * Race
  * Number of visits
  * Time in hospital
  * Medications
  * Readmission status

---

## ⚙️ Tech Stack

* Python (Pandas, NumPy, Scikit-learn)
* Jupyter Notebook
* Power BI
* SHAP (for model explainability)

---

## 🔄 Project Workflow

### 1. Data Preprocessing

* Handled missing values
* Converted categorical variables
* Removed irrelevant columns

### 2. Feature Engineering

* Created new features:

  * Total visits
  * High utilization flag
* One-hot encoding for categorical data

### 3. Model Building

* Logistic Regression used as baseline model
* Train-test split applied
* Model evaluation performed

### 4. Dashboard Development

Built an interactive Power BI dashboard including:

* 📊 Readmission Rate KPI
* 👥 Total Patients
* 📈 Readmission by Age Group
* 📉 Readmission vs Total Visits
* 🔁 High Utilization Analysis
* 🥧 Readmission Distribution (Pie Chart)
* 🎛️ Slicers:

  * Age Group
  * Gender
  * Race

---

## 📊 Key Insights

* Older patients show higher readmission rates
* Patients with more visits have higher risk
* High utilization patients require special attention
* Demographic patterns affect readmission probability

---

## 📁 Files in Repository

* `PatientReadmission.ipynb` → Data analysis & model
* `final_data.csv` → Processed dataset
* `Dashboard.pbix` → Power BI dashboard

---

## 🚀 How to Run

### Python

```bash
pip install pandas numpy scikit-learn shap
```

Open:

```bash
PatientReadmission.ipynb
```

### Power BI

* Open `Dashboard.pbix`
* Refresh data if needed



## 💡 Conclusion

This project demonstrates how data analysis and visualization can help healthcare systems reduce readmission rates and improve patient care.


