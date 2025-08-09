# 🧹 Cleaned & Refined Messy Rows Dataset  

**Title:** Data Cleaning and Transformation using Power Query...
**Project Type:** Data Cleaning & Transformation  
**Duration:** Jun 2025 – Jun 2025  
**Skills Used:** Microsoft Advanced Excel | Power Query  

---

## 📖 Overview  

This project showcases a **real-world data cleaning and transformation process** using **Microsoft Power Query** and **Advanced Excel**.  
The primary objective was to **convert raw, unstructured data into an analysis-ready format**, ensuring accuracy, clarity, and consistency across all fields.  

The dataset had **multiple data quality issues**, including:  
- Duplicate columns  
- Inconsistent casing (Uppercase, lowercase, mixed)  
- Merged columns containing multiple values  
- Numerous null or blank values  
- Fragmented city names across columns  
- Improper data type assignments  

By leveraging Power Query’s robust features, I systematically transformed this messy dataset into a clean and structured one — ready for accurate analysis and reporting.  

---

## 🛠 Problem Statement  

Modern business decisions rely on **clean, accurate, and consistent data**.  
However, raw datasets from multiple sources often contain errors, inconsistencies, and structural problems.  
If left unaddressed, these issues can lead to:  
- Wrong analysis results  
- Poor decision-making  
- Increased time in manual corrections  

This project aimed to **automate and streamline the cleaning process** using **Power Query** — reducing manual effort while improving efficiency.  

---

## 🔍 Data Issues Identified  

1. Multiple duplicate and unnecessary columns.  
2. Inconsistent text formatting, making it difficult to group or sort values.  
3. Merged cells with unrelated information combined in a single field.  
4. Blank and null values across important columns.  
5. City names split incorrectly into multiple columns.  
6. Columns placed in random, non-logical order.  
7. Incorrect data types (e.g., text stored as numbers or vice versa).  

---

## 🛠 Step-by-Step Data Cleaning Process  

### **1. Converting Raw Data into a Structured Table**  
- Converted the dataset into an **Excel table** for structured processing.  
- Imported the table into **Power Query Editor**.  

### **2. Standardizing Text Case**  
- Applied **Capitalize Each Word** transformation to improve readability and uniformity.  

### **3. Splitting and Removing Columns**  
- Used **Split Column by Delimiter** to separate merged values.  
- Deleted blank or duplicate columns to simplify the dataset.  

### **4. Merging Fragmented City Columns**  
- Combined separated city name columns (e.g., `"New"` + `"York"` → `"New York"`).  

### **5. Handling Missing Values**  
- Filled blank cells with `"N/A"` or other relevant placeholders to avoid null-related issues in analysis.  

### **6. Using ‘Columns from Examples’ for Complex Extraction**  
- Extracted values from complex columns without manual splitting.  

### **7. Reordering Columns Logically**  
- Arranged fields in a logical order (e.g., IDs → Names → Contact → Location → Metrics).  

### **8. Detecting and Assigning Data Types**  
- Used **Detect Data Type** to assign correct formats (Text, Number, Date).  

### **9. Ensuring Consistency in Key Fields**  
- Converted **Working ID** and **Email** fields to lowercase for uniformity.  

### **10. Exporting the Clean Dataset**  
- Loaded the transformed data back into Excel for further analysis.  

---

## 📊 Tools & Technologies Used  

- **Microsoft Excel (Advanced)** — For table creation and exporting.  
- **Power Query** — For automating data cleaning and transformation.  
- **Data Profiling Tools** — For detecting nulls, duplicates, and inconsistent formats.  

---

## 📁 Files Included in This Repository  

| File Name | Description |
|-----------|-------------|
| `Cleaned & Refined Messy Rows Dataset.pdf` | Detailed explanation of the cleaning and transformation process. |
| `Messy Employee Dataset 2000.csv` | Raw messy dataset in CSV format. |
| `Messy Employee Dataset 2000.xlsx` | Raw dataset in Excel format. |
| `Data Cleaning.png` | Snapshot showing the cleaned dataset in Excel. |

---

## 💡 Key Learning Outcomes  

- Practical application of **Power Query** for large dataset cleaning.  
- Experience in **text standardization**, **null handling**, and **data type management**.  
- Skills in **automating repetitive tasks** to improve data quality.  
- Ability to convert messy, unstructured data into a clean, analysis-ready format.  

---

## 🚀 How to Use This Project  

1. **Download or Clone** the repository.  
2. Open the `.csv` or `.xlsx` file to explore the raw dataset.  
3. Review the **PDF documentation** to understand each transformation step.  
4. Open the cleaned Excel file to view the final, analysis-ready dataset.  

---

## 🌟 Future Enhancements  

- Automating the process entirely using **Power BI Dataflows**.  
- Adding **custom validation rules** for incoming raw data.  
- Building a **Power BI dashboard** to visualize before-and-after comparisons.  

---
## 📷 Dataset Snapshot  

![Data Cleaning](./Data%20Cleaning.png)

