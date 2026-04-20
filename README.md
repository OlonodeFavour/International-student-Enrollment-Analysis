# International-student-Enrollment-Analysis


![Tool](https://img.shields.io/badge/Tool-Looker%20Studio-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Type](https://img.shields.io/badge/Project-Student%20Enrollment%20Analysis-blue)


---

## 📌 Overview
This project presents an interactive **SEVIS Student Dashboard** built using **Looker Studio**, designed to analyze international student records, academic majors, and SEVIS I-901 fee transactions.

The dashboard transforms raw data into meaningful insights, enabling stakeholders to monitor student enrollment trends, evaluate program demand, and analyze fee payment patterns.

---

## ❗ Problem Statement
Educational institutions often face challenges in analyzing international student data due to large datasets and lack of visualization tools.

Key issues include:
- Difficulty identifying high-demand academic programs  
- Limited visibility into SEVIS fee revenue distribution  
- Poor tracking of payment trends over time  
- Challenges in analyzing student enrollment patterns  

This project addresses these challenges by providing an interactive and visually intuitive dashboard.

---

## 🛠️ Tools Used
- **Looker Studio (Google Data Studio)**
- **Google Sheets** (Data Source)


---

## 🔗 Data Source and Connection
The dataset used is a **SEVIS student records dataset**, containing:
- International student information  
- Academic majors  
- SEVIS I-901 fee transactions  

### **Connection Process**
1. Cleaned and prepared the dataset (correct data types and structure)  
2. Uploaded the dataset to **Google Sheets**  
3. Connected Google Sheets to **Looker Studio**  
4. Validated field types (dates, numeric values, text fields)  
5. Built visualizations using the connected data source  

---

## 🧹 Data Cleaning and Preparation
To ensure accuracy and usability, the following steps were performed:
- Verified and corrected data types (dates, numbers, text)  
- Cleaned inconsistent entries  
- Structured dataset for analysis  
- Ensured transaction dates and amounts were properly formatted  

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was conducted to understand patterns within the dataset:

- Analyzed student distribution across majors  
- Evaluated SEVIS fee contributions by program  
- Examined trends in fee payments over time  
- Identified dominant and underrepresented majors  

---

## 📊 Dashboard Design Summary

### **Chart Types and Rationale**
- **Scorecards** → Display key KPIs (Total Students, Total Majors, Total SEVIS Fees)  
- **Bar Charts** → Compare enrollment and fee distribution across majors  
- **Time Series (Line Chart)** → Visualize SEVIS fee payment trends over time  

---

### **🎨 Colour Theme and Layout**
- Clean and neutral design for professionalism  
- Blue color palette for clarity and consistency  
- KPIs positioned at the top for quick insights  
- Logical top-down layout:
  - KPIs → Enrollment → Fee Analysis → Trends  

---

### **⚙️ Filters and Interactivity**
- Date range filter for time-based analysis  
- Major selection filter for focused insights  
- Cross-filtering between charts  
- Dynamic KPI updates based on user interaction  

---

## 📈 Results and Findings

### **Key Patterns and Trends**
- A few majors account for a large share of total enrollment  
- Technology-related majors dominate student interest  
- SEVIS fee payments show a declining trend over time  

---

### **Notable Distributions**
- Uneven fee distribution across majors  
- “Others” category contributes significantly to total fees  

---

### **Insights**
- Higher enrollment leads to higher fee revenue  
- Demand is concentrated in specific academic programs  
- Payment patterns align with admission cycles  

---

## ⚠️ Challenges and Solutions
- **Uniform SEVIS status values** limited comparisons  
  - ✔️ Resolved by redefining eligibility context  

- **Long major names affected readability**  
  - ✔️ Resolved using horizontal bar charts  

- **Date aggregation issues**  
  - ✔️ Fixed by setting transaction date as primary date field  

---

## 💡 Recommendations
Based on the analysis, the following actions are suggested:

- Expand capacity for high-demand majors  
- Promote underrepresented academic programs  
- Monitor fee payment cycles for better planning  
- Improve data categorization for clearer insights  
- Use trends to guide policy and enrollment strategies  

---

## 📷 Dashboard Preview





<img width="912" height="628" alt="Sevis dashboard" src="https://github.com/user-attachments/assets/a15fe846-c0f6-45d5-a5e8-d0383a97f2cc" />

