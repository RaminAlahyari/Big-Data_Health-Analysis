# Big Data Analytics in Healthcare using PySpark

## 📌 Project Overview
This project applies **Big Data Analytics** techniques using **Apache PySpark** to analyze **post-surgery recovery times** based on various factors such as **demographics, surgery details, and lifestyle choices**.

## 🚀 Key Tasks & Implementation
### **1️⃣ Task 1: Average Recovery Time Using Demographic Factors**
- **Objective**: Analyze the impact of **age** and **diabetes status** on post-surgical recovery time.
- **Features Used**:
  - **Age Groups** (18-30, 31-45, 46-60, etc.)
  - **Diabetes Status** (Yes/No)
- **Approach**: Compute **average recovery time** across different demographic groups using **PySpark RDDs**.
- **Findings**: No significant difference in recovery time based on diabetes status and age.

### **2️⃣ Task 2: Maximum Recovery Time Using Surgery Details**
- **Objective**: Identify the surgery type, duration, and anesthesia type that lead to **longest recovery time**.
- **Features Used**:
  - **Type of Surgery** (Knee Replacement, Heart Bypass)
  - **Surgery Duration** (1-10 hours)
  - **Anesthesia Type** (General, Local)
- **Approach**: Aggregate recovery times to find the **maximum recovery period** for each combination.
- **Findings**: The longest recovery time (30 days) was associated with **Knee Replacement surgery (5-hour duration, General Anesthesia)**.

### **3️⃣ Task 3: Average Recovery Time Using Lifestyle Factors**
- **Objective**: Examine how **smoking and alcohol consumption** impact recovery time.
- **Features Used**:
  - **Smoking Status** (Smoker, Non-Smoker)
  - **Alcohol Use** (Yes, No)
- **Approach**: Group patients into four lifestyle categories and compute **average recovery time**.
- **Findings**: No significant impact of smoking or alcohol use on recovery time in this dataset.

---

## 🛠 Tools & Technologies
- **Apache PySpark** for big data processing
- **Google Colab** for execution
- **RDDs** for distributed computation
- **Synthetic Healthcare Dataset** (100,000 records)

---

## 📈 Results Summary
| Task | Key Finding |
|------|------------|
| **Task 1** | No major impact of diabetes and age on recovery time |
| **Task 2** | Knee replacement (5-hour duration, general anesthesia) had the longest recovery time (30 days) |
| **Task 3** | Smoking and alcohol use did not significantly alter recovery time |

---

## 🔥 Future Enhancements
- **Extend dataset** to real-world patient data for validation.
- **Feature Engineering** for more granular analysis (e.g., diet, exercise, medical history).
- **Advanced ML Models** to predict recovery time using Spark MLlib.

---

## 📬 Contact
For any questions or collaboration, feel free to reach out via **GitHub Issues**.

_⭐ If you find this project useful, consider giving it a star! ⭐_
