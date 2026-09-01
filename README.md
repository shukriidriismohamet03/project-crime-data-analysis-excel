# 🚔 Crime Data Analysis inroduction

## 📌 Project Overview

This project analyzes crime data using **Microsoft Excel**. The main purpose of the project was to clean the crime dataset, analyze crime incidents, and present the results using **Excel formulas, PivotTables, PivotCharts, and an interactive Dashboard**.

The analysis focuses on identifying important patterns related to:

* Crime Types
* Districts
* Case Status
* Victim Gender
* Severity Level
* Crime Trends

---

## 🎯 Project Objectives

The objectives of this project were to:

* Clean the crime dataset.
* Identify and remove duplicate records.
* Handle missing and invalid values.
* Standardize inconsistent data.
* Perform data analysis using Excel formulas.
* Create PivotTables and PivotCharts.
* Design a crime analysis dashboard.
* Identify important crime patterns and trends.
* Provide useful findings and recommendations.

---

## 📂 Dataset Description

The dataset contains information about reported crime incidents.

### Dataset Summary

| Description                     | Records |
| ------------------------------- | ------: |
| Original Records                |     300 |
| Duplicate Records Removed       |       8 |
| Final Cleaned Records           |     292 |
| Total Missing Values Identified |     142 |

### Dataset Columns

The dataset includes the following variables:

| Column         | Description                                  |
| -------------- | -------------------------------------------- |
| Crime ID       | Unique identifier for each crime record      |
| Crime Date     | Date when the crime occurred or was recorded |
| Crime Type     | Category of the reported crime               |
| District       | District where the crime was reported        |
| Victim Gender  | Gender of the recorded victim                |
| Case Status    | Current status of the crime case             |
| Severity Level | Level of crime severity                      |

---

## ⚠️ Problems Found in the Dataset

Before performing the analysis, the dataset was inspected for data-quality issues.

The following problems were identified:

* **8 duplicate records**
* Missing values across multiple columns
* Invalid or inconsistent entries and formatting

### Missing Values

| Column         | Missing Values |
| -------------- | -------------: |
| ID             |             15 |
| Crime_Date     |             17 |
| Crime_Type     |             15 |
| District       |             16 |
| Gender         |             45 |
| Case_Status    |             16 |
| Severity_Level |             18 |
| **Total**      |        **142** |

The Gender column contained the highest number of missing values.

---

## 🧹 Data Cleaning Process

The following data-cleaning steps were performed:

* Removed 8 duplicate records.
* Identified a total of 142 missing values.
* Reviewed missing ID values.
* Reviewed missing Crime_Date values.
* Handled missing Crime_Type values.
* Handled missing District values.
* Reviewed missing Gender values.
* Handled missing Case_Status values.
* Reviewed missing Severity_Level values.
* Standardized inconsistent text entries.
* Checked the cleaned dataset for consistency before analysis.

After removing duplicate records, the final dataset contained **292 records**.

---

## 🛠️ Tools and Techniques Used

**Tool Used:** Microsoft Excel

### Excel Features Used

* Data Cleaning
* Excel Formulas and Functions
* PivotTables
* PivotCharts
* Dashboard Creation
* Data Visualization

### Excel Formulas and Functions

| Formula / Function | Purpose                                    |
| ------------------ | ------------------------------------------ |
| `COUNTA`           | Count total crime records                  |
| `COUNTIF`          | Count crimes according to categories       |
| `COUNTIFS`         | Count records based on multiple conditions |
| `TRIM`             | Remove extra spaces                        |
| `PROPER`           | Standardize text capitalization            |
| `UPPER`            | Convert text to uppercase                  |
| `LOWER`            | Convert text to lowercase                  |
| `YEAR`             | Extract year from Crime Date               |
| `MONTH`            | Extract month from Crime Date              |
| `IF`               | Create data-quality and status conditions  |

---

# 📊 Data Analysis

The cleaned dataset was analyzed using Excel formulas, PivotTables, PivotCharts, and a dashboard.

## Key Metrics

| Metric                    |     Result |
| ------------------------- | ---------: |
| Total Crime Incidents     |        292 |
| Most Common Crime Type    | Theft – 85 |
| Highest Crime District    | Hodan – 84 |
| High Severity Incidents   |        106 |
| Medium Severity Incidents |        156 |
| Low Severity Incidents    |         30 |
| Closed Cases              |        123 |
| Open Cases                |         67 |
| Under Investigation       |         77 |
| Referred Cases            |         25 |
| Male Victims              |        160 |
| Female Victims            |         89 |
| Unknown Gender            |         43 |

---

## 🔍 Crime Type Analysis

Theft was identified as the most common crime type.

| Crime Type      | Number of Incidents |
| --------------- | ------------------: |
| Theft           |                  85 |
| Assault         |                  60 |
| Fraud           |                  57 |
| Robbery         |                  44 |
| Traffic Offense |                  28 |
| Burglary        |                  18 |

---

## 📍 District Analysis

**Hodan** recorded the highest number of reported crimes with **84 incidents**.

Other districts include:

| District | Number of Incidents |
| -------- | ------------------: |
| Hodan    |                  84 |
| Wadajir  |                  62 |
| Yaqshid  |                  44 |
| Daynile  |                  38 |
| Karan    |                  32 |
| Waberi   |                  32 |

---

## 📁 Case Status Analysis

| Case Status         | Number of Cases |
| ------------------- | --------------: |
| Closed              |             123 |
| Under Investigation |              77 |
| Open                |              67 |
| Referred            |              25 |

The analysis shows that while many cases have been closed, a considerable number remain **Open or Under Investigation**.

---

## ⚠️ Severity Level Analysis

| Severity Level | Number of Incidents |
| -------------- | ------------------: |
| Medium         |                 156 |
| High           |                 106 |
| Low            |                  30 |

Medium-severity incidents represent the largest category. High-severity incidents also represent a significant portion of the total reported crimes.

---

# 📈 Dashboard

An Excel dashboard was created to present the main insights visually.

The dashboard helps users monitor:

* Total crime incidents
* Crime types
* Crimes by district
* Case status
* Severity levels
* Victim gender
* Crime trends over time

The dashboard uses **PivotTables and PivotCharts** to make the analysis easier to understand and support data-driven decision-making.

---

# 💡 Key Findings

* 📍 **Hodan** has the highest number of reported crimes, with **84 incidents**.
* 🚨 **Theft** is the most common crime type, with **85 incidents**.
* ⚠️ **Medium-severity** incidents are the largest category, with **156 cases**.
* 🔴 **106 incidents** are classified as high severity.
* ✅ **123 cases** are closed.
* 🔄 **67 cases** remain open.
* 🔎 **77 cases** are under investigation.
* 👤 Male victims represent the largest recorded gender group, with **160 incidents**.
* 🧹 The dataset contained significant missing and unknown information that required cleaning before analysis.

---

# 💭 Strategic Recommendations

Based on the analysis, the following recommendations were made:

1. **Increase police resources** in Hodan and Wadajir because these districts recorded high numbers of reported crimes.
2. **Strengthen theft prevention** through public awareness, surveillance, and community policing.
3. **Create a case-clearance team** to focus on Open and Under Investigation cases.
4. **Improve data quality** by reducing missing and unknown values in crime records.
5. **Improve coordination** between police and relevant authorities for Referred cases.
6. **Monitor high-severity incidents** and prioritize resources toward serious crimes.
7. **Continue using the Excel dashboard** to monitor crime trends and support evidence-based decision-making.

---

# 📁 Project Structure

```text
Crime-Data-Analysis/
│
├── CRIME-DATA-ANALYSIS-COMPLA.xlsx
├── Crime_Data_Analysis_Documentation.pdf
└── README.md
```

---

# 📚 Skills Demonstrated

This project demonstrates the following data analysis skills:

* Data Cleaning
* Data Quality Assessment
* Missing Value Analysis
* Duplicate Detection and Removal
* Data Standardization
* Excel Formulas and Functions
* PivotTables
* PivotCharts
* Data Visualization
* Dashboard Development
* Data Interpretation
* Strategic Recommendations

---

# 👩‍💻 Author

**Shukri Idiris Mohamet**

Computer Science Graduate | Aspiring Data Analyst

---

# 📝 Conclusion

This project successfully cleaned, analyzed, and visualized crime data using **Microsoft Excel**.

Excel formulas, PivotTables, PivotCharts, and Dashboards were used to transform raw crime data into meaningful information. The analysis identified important crime patterns, including the high number of crimes in Hodan, the high frequency of Theft, significant High and Medium severity cases, and the number of cases that remain Open or Under Investigation.

Overall, this project demonstrates a complete data analysis workflow—from **data cleaning and preparation to analysis, visualization, and strategic recommendations**.
