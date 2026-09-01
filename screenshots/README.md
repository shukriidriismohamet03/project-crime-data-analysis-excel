# 🚔 Crime Data Analysis Dashboard

## 📌 Project Overview

This project analyzes crime data using **Microsoft Excel**. The project focuses on transforming raw crime data into meaningful insights through:

- Data Cleaning
- Missing Value Analysis
- Duplicate Detection and Removal
- Excel Formulas and Functions
- PivotTables
- PivotCharts
- Interactive Dashboard Creation

The analysis explores crime patterns based on **crime type, district, case status, severity level, and victim gender**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Clean and prepare the crime dataset.
- Identify and remove duplicate records.
- Identify and handle missing values.
- Standardize inconsistent data.
- Analyze crime incidents using Excel.
- Create PivotTables and PivotCharts.
- Develop an interactive crime analysis dashboard.
- Identify important crime patterns.
- Provide useful findings and recommendations.

---

## 🛠️ Tools Used

- **Microsoft Excel**
- Excel Formulas and Functions
- PivotTables
- PivotCharts
- Slicers
- Data Visualization
- Dashboard Design

---

## 📂 Dataset Description

The dataset contains information about reported crime incidents.

### Dataset Summary

| Description | Total |
|---|---:|
| Original Records | 300 |
| Duplicate Records Removed | 8 |
| Final Cleaned Records | 292 |
| Missing Values Identified | 142 |

### Dataset Columns

| Column | Description |
|---|---|
| Crime_ID | Unique identifier for each crime |
| Crime_Date | Date of the reported crime |
| Crime_Type | Type of crime committed |
| District | District where the crime occurred |
| Gender | Victim gender |
| Case_Status | Current status of the case |
| Severity_Level | Severity level of the crime |

---

# 🧹 Data Cleaning

The dataset was inspected before analysis to identify data-quality problems.

### Cleaning Activities

- Removed duplicate records.
- Identified missing values.
- Reviewed missing IDs.
- Reviewed missing crime dates.
- Handled missing crime types.
- Handled missing district values.
- Reviewed missing gender values.
- Handled missing case status values.
- Handled missing severity levels.
- Standardized inconsistent text entries.
- Checked the cleaned data for consistency.

After removing duplicates, the dataset was reduced from **300 records to 292 cleaned records**.

---

# 📊 Data Analysis and Visualizations

## 1️⃣ Crime Type Analysis

![Crime Type Analysis](screenshots/crime-type.png)

### 📌 Interpretation

The **Crime Type PivotTable** shows the distribution of crimes across different categories.

| Crime Type | Number of Incidents |
|---|---:|
| Theft | 85 |
| Assault | 60 |
| Fraud | 57 |
| Robbery | 44 |
| Traffic Offense | 28 |
| Burglary | 18 |
| **Total** | **292** |

### 🔎 Key Insight

As shown in the **Crime Type Analysis image**, **Theft is the most common crime type with 85 incidents**.

**Burglary is the least common crime type with 18 incidents**.

This suggests that theft prevention should be an important priority for crime prevention strategies.

---

## 2️⃣ Case Status Analysis

![Case Status Analysis](screenshots/case-satus.png)

### 📌 Interpretation

The **Case Status chart** visualizes the number of crime cases based on their current status.

The case categories include:

- Closed
- Open
- Referred
- Under Investigation

### 🔎 Key Insight

As shown in the **Case Status Analysis image**, **Closed cases represent the largest category**, while a significant number of cases remain **Open or Under Investigation**.

This indicates that although many cases have been successfully closed, there is still a need to improve case management and investigation processes.

---

## 3️⃣ District Analysis

![District Analysis](screenshots/distric.png)

### 📌 Interpretation

The **District Analysis chart** compares the number of crime incidents across different districts.

The districts displayed include:

- Daynile
- Hodan
- Karan
- Waberi
- Wadajir
- Yaqshid

### 🔎 Key Insight

As shown in the **District Analysis image**, **Hodan has the highest number of reported crimes, with approximately 84 incidents**.

Other districts also show significant crime activity, particularly:

- Wadajir
- Yaqshid
- Daynile

This analysis helps identify districts that may require increased security resources and crime prevention efforts.

---

## 4️⃣ Interactive Crime Analytics Dashboard

![Crime Analytics Dashboard](screenshots/dashboard1.png)

### 📌 Dashboard Features

The **Crime Analytics & Dashboard Control Center** provides an interactive overview of the crime dataset.

The dashboard includes the following Key Performance Indicators (KPIs):

| KPI | Value |
|---|---:|
| Total Incidents | 292 |
| Closed Cases | 123 |
| High Severity Incidents | 106 |
| Open / Under Investigation | 144 |

### 📊 Dashboard Visualizations

The dashboard contains:

- **Crimes by District** chart
- **Case Status** chart
- **District Slicer**
- **Crime Type Slicer**
- **Case Status Slicer**

### 🔎 Interpretation

As shown in the **Dashboard image**, the dashboard allows users to filter and interact with the data using slicers.

Users can analyze crime incidents by:

- District
- Crime Type
- Case Status

The dashboard makes it easier to explore the data and quickly identify important patterns.

---

# 📈 Key Findings

Based on the analysis and visualizations:

- 📌 The dataset contains **292 cleaned crime records**.
- 🚨 **Theft** is the most common crime type with **85 incidents**.
- 📍 **Hodan** recorded the highest number of reported crimes.
- ⚠️ There are **106 high-severity incidents**.
- ✅ **123 cases** are closed.
- 🔄 A significant number of cases remain open or under investigation.
- 📊 The interactive dashboard allows users to filter crime data using slicers.
- 🧹 The original dataset required significant cleaning due to missing values and duplicate records.

---

# 💡 Strategic Recommendations

Based on the analysis, the following recommendations are suggested:

### 1. Increase Resources in High-Crime Districts

Districts with higher crime levels, especially **Hodan**, should receive additional security resources and attention.

### 2. Strengthen Theft Prevention

Since **Theft is the most common crime type**, authorities should strengthen:

- Community awareness
- Surveillance systems
- Community policing
- Theft prevention programs

### 3. Improve Case Management

A dedicated team could focus on:

- Open cases
- Cases under investigation
- Referred cases

This may help improve case resolution rates.

### 4. Improve Data Quality

Future crime records should reduce:

- Missing values
- Unknown values
- Duplicate records
- Inconsistent formatting

### 5. Monitor High-Severity Crimes

High-severity incidents should be closely monitored to support better resource allocation and public safety planning.

---

# 🖼️ Project Screenshots

The project includes the following visualizations:

| Screenshot | Description |
|---|---|
| 📊 Crime Type Analysis | Shows the number of incidents for each crime category |
| 📁 Case Status Analysis | Shows the distribution of cases by their current status |
| 📍 District Analysis | Compares crime incidents across districts |
| 📈 Interactive Dashboard | Provides an overall interactive view of the crime data |

---

# 📁 Project Structure

```text
Crime-Data-Analysis/
│
├── CRIME-DATA-ANALYSIS-COMPLA.xlsx
│
├── Crime_Data_Analysis_Documentation.pdf
│
├── README.md
│
└── screenshots/
    ├── crime-type.png
    ├── case-satus.png
    ├── distric.png
    └── dashboard1.png
