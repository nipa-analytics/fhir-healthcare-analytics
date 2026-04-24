# FHIR Healthcare Analytics
Healthcare analytics project using HL7 FHIR APIs, Python and machine learning
# 🏥 FHIR Healthcare Analytics using HL7 FHIR APIs

## 📌 Project Overview
This project demonstrates an end-to-end healthcare analytics workflow using **HL7 FHIR resources** (Patient, Observation, Condition) to extract, clean, analyze, and visualize clinical data from a public FHIR server.

Using Python and machine learning techniques, this project transforms raw interoperable healthcare data into actionable insights for patient segmentation, trend analysis, and risk-oriented analytics.

---

## 🎯 Business Problem
Healthcare systems generate large amounts of complex interoperable data, but extracting meaningful insights remains challenging.

This project addresses:

- Patient demographic analysis
- Disease prevalence exploration
- Clinical observations trend analysis
- Patient clustering and risk segmentation
- Detection of anomalies and data quality issues

---

## ⚙️ Tech Stack

- Python
- Pandas
- Requests
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
- HL7 FHIR APIs

---

## 📂 FHIR Resources Used

### Patients
Extracted:
- Patient ID
- Gender
- Birth Date / Age

### Observations
Extracted:
- Vital/lab measurements
- Observation timestamps
- Observation values

### Conditions
Extracted:
- Diagnoses / disease conditions
- Patient-condition relationships

Data Source:
Public HAPI FHIR R4 Server

https://hapi.fhir.org/baseR4

---

## 🔄 Workflow

1. Extract FHIR resources via REST APIs  
2. Normalize nested FHIR JSON structures  
3. Clean missing timestamps and inconsistent values  
4. Perform exploratory data analysis  
5. Analyze trends in clinical observations  
6. Apply clustering for patient segmentation  
7. Identify anomalies and outliers

---

## 📊 Exploratory Analysis

### Patient Demographics
- Gender distribution
- Age distribution

### Clinical Insights
- Most common conditions
- Average vitals per patient
- Missing data pattern analysis

---

## 🤖 Machine Learning: Patient Segmentation

K-Means clustering was used to group observations into clusters representing potential:

- Lower-risk patterns
- Moderate-risk patterns
- Anomalous/high-risk observations

Outlier detection revealed the importance of healthcare data quality validation.

---

## 📈 Sample Visualizations

### Gender Distribution
(Add image here)

### Age Distribution
(Add image here)

### Condition Frequency
(Add image here)

### Observation Clustering
(Add image here)

---

## 🔍 Key Findings

- Identified recurring disease prevalence patterns
- Revealed variability in patient observation trends
- Detected natural groupings in observation data
- Surfaced anomalous observations suggesting data quality or risk signals

---

## 💼 Business / Clinical Value

This project supports:
- Population health analytics
- Risk stratification
- Clinical monitoring insights
- Interoperability-driven analytics use cases

---

## 🚀 Future Enhancements

- Readmission risk prediction model
- Streamlit interactive dashboard
- FHIR + SQL data pipeline
- Predictive healthcare analytics
- Real EHR/FHIR integration

---

## 📦 Installation

```bash
conda create -n fhir_env python=3.10
conda activate fhir_env
pip install -r requirements.txt
jupyter notebook
```

---

## requirements.txt

```text
numpy<2
pandas
requests
matplotlib
scikit-learn
``

Open:

```bash
FHIR_Healthcare_Analysis.ipynb
```
```

---

## 🌟 Key Skills Demonstrated

- HL7 FHIR
- Healthcare Analytics
- API Data Extraction
- Data Cleaning
- Time Series Analysis
- Unsupervised Machine Learning
- Patient Segmentation

---

## 👤 Author
Nipa Shah

If you found this interesting, feel free to connect or contribute.
