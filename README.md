# advanced-data-quality-profiling

##  Overview
This project focuses on evaluating the quality of sensor data and detecting anomalies using statistical techniques. The objective is to ensure data reliability by identifying inconsistencies, outliers, and abnormal patterns before further analysis or deployment in real-world systems.

The analysis is performed using Python in a Jupyter Notebook environment, following a structured and reproducible workflow.



## 🛠 Technologies Used
- Python  
- pandas  
- numpy  
- scipy  
- Jupyter Notebook  

---

## 📂 Dataset
The dataset consists of time-series sensor readings, including:
- Time  
- Temperature  
- Humidity  
- Light  
- Loudness  

A column with zero variance was identified and removed during profiling to improve data relevance.

---

## 🔍 Methodology

### 1️⃣ Data Profiling
- Checked for missing values and completeness
- Calculated missing value percentages
- Analyzed unique value counts
- Generated descriptive statistics to understand distributions

### 2️⃣ Anomaly Detection
Two statistical techniques were applied:
- **Z-Score Method** to detect extreme deviations
- **Interquartile Range (IQR)** to identify spread-based outliers

Both methods were used to compare anomaly sensitivity and ensure robustness.

### 3️⃣ Data Cleaning
- Outliers were identified and handled without blindly removing records
- Data integrity was preserved
- A cleaned dataset was generated for downstream use

---

## 📊 Key Insights
- No missing values were present in the dataset
- Statistical profiling revealed realistic sensor behavior
- Anomalies were successfully detected using both Z-Score and IQR methods
- Cleaned data was exported for reuse and reporting

---
## How to Run 
1. Clone the repository
2. Install dependencies using requirements.txt
3. Run the Jupyter Notebook

## Author 
Anshika Patel

---
This project demonstrates practical data quality assessment and anomaly detection techniques commonly used in real-world data analytics workflows.
