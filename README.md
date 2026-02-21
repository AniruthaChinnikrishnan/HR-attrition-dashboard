# **HR Attrition Analytics Dashboard (Power BI)**

This repository contains an end-to-end **HR analytics dashboard project** built using **Power BI**, focused on analyzing employee attrition patterns and identifying key factors influencing workforce turnover.

The project demonstrates skills in **transformation, modeling, DAX calculations, and dashboard storytelling** using the IBM HR Analytics dataset.

---

## **Project Overview**

Employee attrition is a critical business challenge that impacts productivity, hiring costs, and organizational stability.

This dashboard provides:

* A comprehensive **attrition overview**  
* Identification of **key drivers of employee turnover**  
* Analysis of **demographics and behavioral patterns**  
* Department-level and gender-based attrition comparisons  
* Actionable insights for HR decision-making

The dashboards were developed using **Microsoft Power BI**, with the **IBM HR Analytics dataset** as the data source.

---

## **Tools & Technologies Used**

* **Power BI Desktop**  
* **Power Query**  
  * Data cleaning and transformation  
  * Creation of derived columns  
* **DAX (Data Analysis Expressions)**  
  * Custom measures for KPIs and comparisons  
* Data Visualization & Dashboard Design Principles

---

## **Data Preparation (Power Query)**

The dataset was carefully cleaned and structured to ensure accuracy and usability.

### **New Columns Created**

The following calculated columns were added using Power Query to improve analysis clarity:

* **Age Group**  
* **Working Years Group**  
* **Job Satisfaction Status**  
* **Distance Status**

All missing values, inconsistencies, and formatting issues were handled to maintain clean data integrity.

---

## **DAX Measures Created**

A total of **12 custom measures** were created:

1. Total Employees  
2. Total Attrition  
3. Attrition Rate  
4. Male Attrition Rate  
5. Female Attrition Rate  
6. Overtime Attrition  
7. HR Attrition  
8. Remaining HR Attrition  
9. R\&D Attrition  
10. Remaining R\&D Attrition  
11. Sales Attrition  
12. Remaining Sales Attrition

These measures enabled advanced KPI tracking and departmental comparisons.

---

# **Dashboard Pages & Insights**

---

# **Employee Attrition Overview**

This page provides a high-level snapshot of workforce attrition across multiple dimensions.

### **Key Metrics**

* **Total Employees:** 1,470  
* **Overall Attrition Rate:** 16.12%

### **Visual Analysis**

#### **Attrition by Working Years**

* The majority of attrition occurs within **0–10 years** tenure.  
* Indicates early-career turnover risk and possible onboarding or engagement gaps.

#### **Attrition by Distance to Work**

* Employees living **near the workplace** show the highest attrition count.  
* Suggests distance alone may not be the primary retention factor.

#### **Attrition by Department**

* **The R & D department** has the highest attrition volume.  
* Sales follows, while HR has the lowest attrition.

#### **Gender Attrition**

* Male attrition is significantly higher than female attrition.  
* May indicate role distribution imbalance or workforce composition differences.

### 

### 

### 

### **Insight**

Early-career employees and technical departments require targeted retention strategies such as:

* Career growth programs  
* Mentorship initiatives  
* Engagement improvement

---

# **Factors Influencing Employee Attrition**

This page focuses on identifying the main drivers behind employee turnover.

### **Attrition by Job Roles**

* Highest attrition observed among:  
  * Laboratory Technicians  
  * Sales Executives  
  * Research Scientists  
* Managerial roles show comparatively low attrition.

**Insight:** Operational roles experience more stress, workload, or career stagnation.

---

### **Attrition by Work-Life Balance**

* Employees with **moderate work-life balance (level 3\)** show the highest attrition.  
* Very poor balance does not necessarily correlate with highest exits.

**Insight:** Perception of balance may vary; expectations management is important.

---

### **Attrition by Job Satisfaction**

* Surprisingly, even **highly satisfied employees** show notable attrition.  
* Dissatisfaction still contributes but is not the only factor.

**Insight:** Compensation, growth, or external opportunities may drive exits beyond satisfaction levels.

---

### **Attrition by Environment Satisfaction**

* Lower environment satisfaction corresponds to higher attrition counts.  
* Workplace culture remains a strong retention factor.

---

# **Employee Demographics & Attrition Patterns**

This page analyzes demographic characteristics associated with attrition.

### **Attrition by Education**

* Employees with **Life Sciences and Medical backgrounds** show the highest attrition.  
* Indicates domain-specific turnover patterns.

---

### **Attrition by Age**

* **The 26–35 age group** experiences the highest attrition.  
* Early and mid-career transitions are the most volatile periods.

---

### **Attrition by Marital Status**

* Single employees show higher attrition compared to married employees.  
* Could relate to mobility flexibility or career experimentation.

---

### **Attrition by Overtime**

* Employees working overtime show significantly higher attrition.  
* Strong evidence of workload-related burnout risk.

**Insight**

Reducing excessive overtime and improving workload distribution could directly improve retention.

---

# **Key Overall Insights**

Across all dashboards:

* Early-career professionals are most likely to leave.  
* Overtime and workload imbalance are major attrition drivers.  
* Technical departments experience higher turnover.  
* Satisfaction alone does not guarantee retention.  
* Demographics such as age and marital status influence attrition behavior.