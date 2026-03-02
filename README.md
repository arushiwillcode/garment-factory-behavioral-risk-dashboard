# 📊 Garment Factory Behavioral Risk Dashboard (Power BI)

## 📌 Project Overview

This project analyzes garment factory production team data to identify potential behavioral risk patterns using engineered analytical metrics in Power BI.

The objective was to design a rule-based anomaly detection framework that flags teams exhibiting:

* Elevated overtime pressure
* Operational inconsistency (idle time vs productivity)
* Abnormal productivity stability

The dashboard provides an executive-level risk overview along with a detailed investigation layer.

---

## 🗂 Dataset

* Source: Kaggle (Garment Worker Productivity Dataset)
* Industry: Manufacturing
* Records Used: 691 cleaned observations
* Analytical Unit: Production Teams

---

## 🧠 Analytical Approach

The system was built using custom DAX measures and structured KPI modeling.

### Engineered Metrics:

* **Productivity Gap** (Actual vs Target)
* **Overtime Pressure Flag**
* **Idle Conflict Detection**
* **Team Productivity Standard Deviation**
* **Behavioral Stability Index**
* **Composite Suspicion Score**
* **High Risk Classification**

A multi-factor scoring approach was used to detect teams exhibiting statistically abnormal patterns.

---

## 📈 Key Findings

* 2 teams identified as high-risk based on combined anomaly signals.
* High overtime does not consistently result in higher productivity.
* Teams with unusually stable productivity patterns contribute to elevated suspicion scoring.

---

## 📊 Dashboard Features

* Executive KPI Overview
* Overtime vs Productivity Combo Chart
* Stability Analysis
* Team-Level Risk Investigation Table
* Interactive Filtering

---

## 🛠 Tools & Skills Demonstrated

* Power BI
* DAX (Custom Measures & Aggregation Logic)
* Data Cleaning & Transformation
* Statistical Dispersion Analysis
* Rule-Based Risk Scoring

---

## 💡 Learning Outcome

This project strengthened my understanding of analytical modeling, KPI engineering, and multi-metric anomaly detection using business-oriented logic rather than simple descriptive reporting.

---

