# 📊 Customer Shopping Behavior Analysis — End-to-End Data Analytics Project

## 📝 Overview
This project demonstrates a complete end-to-end data analytics process to understand customer shopping behavior. It includes Python for data cleaning and EDA, SQL for business insights, Power BI for dashboard visualization, and a final report and presentation summarizing key findings.

---

## 📂 Dataset
- Total Records: ~3,900
- Columns: 18 (Demographics, transactions, product details, ratings, discounts, shipping type, etc.)
- Missing Values: 37 missing review ratings (handled during cleaning)
- Stored in Python and later loaded into SQL for deeper analysis

---

## 🛠 Tools & Technologies
| Task | Tool |
|------|------|
| Data Cleaning & EDA | **Python (pandas)** |
| Database & SQL Queries | **MySQL** |
| Dashboard | **Power BI** |
| Report | **PDF** |
| Presentation | **Gamma** |
| Version Control | **GitHub** |

---

## 🚀 Steps Performed

### **1. Data Loading & EDA (Python)**
- Loaded dataset using pandas  
- Reviewed structure using `.info()` and `.describe()`  
- Identified missing values and outliers  
- Visualized trends in purchases, reviews, and categories  

### **2. Data Cleaning**
- Handled missing review ratings using median by category  
- Standardized column names  
- Created new variables:
  - Age groups  
  - Purchase frequency  
- Removed redundant `promo_code_used` field  
- Uploaded cleaned dataset to SQL database

### **3. SQL Analysis**
Examples of business questions answered:
- Revenue comparison by gender  
- Highest-rated products  
- Subscription vs non-subscription behavior  
- Discount-reliant products  
- Shipping method impact on purchase amount  
- Customer segmentation (New, Returning, Loyal)  
- Top items per category  
- Revenue by age group  

### **4. Power BI Dashboard**
Dashboard includes:
- Key KPIs (Avg Purchase Amount, Rating, Customer Count)
- Revenue by Category, Age Group, Subscription Status
- Sales by Category & Age-Group
- Interactive slicers (Gender, Subscription, Category, Shipping Type)

### **5. Report & Presentation**
- A detailed report summarizing insights & recommendations  
- Clean and engaging presentation created using **Gamma**  

---

## 🎯 Key Insights (Sample)
- Repeat customers contribute major revenue share  
- Discounts drive first-time purchases but not loyalty  
- Subscribed customers spend significantly more than non-subscribed customers  
- Age groups 25–40 generate the highest revenue  
- Top-rated products correlate strongly with higher repeat orders  

---

## 📈 Dashboard Preview

<img width="1717" height="1036" alt="image" src="https://github.com/user-attachments/assets/dc8e4c35-810b-465c-b713-d1d1be9e0581" />

---

## 📈 Business Recommendations
- Launch targeted subscription growth campaigns  
- Build loyalty reward programs  
- Optimize discount strategy to balance margin & volume  
- Promote top-rated and frequently purchased products  
- Focus marketing on high-value age groups and express shipping users  

---

## 🧠 What I Learned
- Real-world EDA & cleaning workflows
- Writing SQL queries for business insights
- Creating dashboards for decision-making
- Turning data into strategic recommendations
- Communicating insights clearly through reports and presentations

