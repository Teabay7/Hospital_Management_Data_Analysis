# 🏥 Hospital Management Data Analysis (Python Project)

## 📌 Project Overview
This project analyzes hospital management data covering **patients, doctors, appointments, treatments, and billing** to uncover operational and financial insights.  
Using **Python**, the project focuses on data cleaning, transformation, exploratory analysis, and revenue performance evaluation, highlighting gaps between expected and actual revenue and identifying improvement opportunities.

The findings are presented through both a **Jupyter Notebook** and a **PowerPoint report** for effective analytical storytelling.

---

## 🎯 Objectives
- Analyze hospital revenue performance  
- Identify gaps between expected and actual revenue  
- Evaluate doctor and branch performance  
- Understand appointment and payment trends  
- Provide data-driven recommendations for operational improvement  

---

## 📂 Project Structure
- **Jupyter Notebook**
  - `Hospital Management.ipynb`
- **Presentation**
  - `Hospital_Management_Data_Analysis.pptx`

---

## 🧹 Data Cleaning & Transformation
The dataset was cleaned and transformed using Python by:
- Checking and handling missing values  
- Identifying and removing duplicates  
- Correcting inconsistent data types  
- Dropping irrelevant columns (e.g., appointment_time, bill_date, amount)  

### Feature Engineering
- Created `full_name` columns for patients and doctors  
- Derived patient age from date of birth  
- Built separate **patient** and **doctor** tables  
- Merged all datasets into a single **hospital dataframe** for analysis  

---

## ❓ Key Business Questions Answered
- What is the **expected vs actual revenue**, and how large is the gap?  
- Which **doctors** generate the highest billing?  
- How does revenue vary by **branch and treatment type**?  
- What are the **monthly trends** in appointments and revenue?  
- What is the status of **hospital payments** (successful, pending, failed)?  

---

## 📊 Key Findings

### Revenue Performance
- **Expected Revenue:** $551,249.85  
- **Actual Revenue:** $173,424.90  
- **Revenue Gap:** $377,824.95  
- Only **31.5% of expected revenue** was realized, indicating major payment and billing challenges  

### Appointments & Trends
- April recorded the **highest number of appointments**  
- September recorded the **lowest appointment volume**  
- Expected revenue peaked in April, while actual revenue peaked in June  

### Payments & Insurance
- Most payments were either **pending (34.5%)** or **failed (33.5%)**  
- Credit card payments were the most successful  
- **MedCare Plus Insurance** accounted for over **50% of successful payments**  

### Doctor & Branch Performance
- Certain doctors contributed disproportionately to billing  
- Central Hospital branch outperformed others  
- Chemotherapy and selected treatments generated the highest revenue  

---

## 🛠 Tools & Libraries Used
- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- Jupyter Notebook  

---

## 💡 Recommendations
- Improve payment processing systems to reduce failures and pending payments  
- Strengthen partnerships with high-performing insurance providers  
- Optimize high-revenue treatments such as chemotherapy  
- Replicate best practices from top-performing doctors  
- Apply Central Hospital’s strategies across underperforming branches  

---

## 🎯 Final Conclusion
This project demonstrates the ability to transform raw hospital data into **actionable financial and operational insights** using Python.  
By identifying revenue gaps, performance drivers, and operational inefficiencies, the analysis supports **data-driven decision-making** aimed at improving hospital efficiency, revenue realization, and service delivery.
