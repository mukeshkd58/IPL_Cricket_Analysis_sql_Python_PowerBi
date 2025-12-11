# 📊 IPL Cricket Analysis (2008–2022)
### _SQL • Python • Power BI End-to-End Data Analytics Project_

<p align="center">
  <img src="Dashboard Images/dashboard.png" alt="IPL Dashboard" width="90%">
</p>

---


## 📌 Table of Contents
1. [Project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Tools & Technologies](#tools--technologies)
4. [Dataset Description](#dataset-description)
5. [Data Pipeline](#data-pipeline)
6. [Project Structure](#project-structure)
7. [Key Insights from Dashboard](#key-insights-from-dashboard)
8. [Dashboard Features](#dashboard-features)
9. [How to Run the Project](#how-to-run-the-project)
10. [Future Enhancements](#future-enhancements)
11. [Author](#author)

---

## 🚀 Project Overview
This project performs a complete analytical study of the IPL (Indian Premier League) from **2008 to 2022** using:

- **PostgreSQL** for data handling & transformations  
- **Python** for cleaning & exploratory analysis  
- **Power BI** for dashboard creation  

The dashboard highlights:

- Title winners  
- Orange Cap & Purple Cap players  
- Top batsmen and bowlers  
- Toss impact  
- Match results  
- Venue performance  
- Tournament 4s & 6s statistics  
- Team wins per season  

A perfect demonstration of **SQL + Python + Power BI** integration for a professional and job-ready portfolio.

---

## 🎯 Objectives
- Deep dive into IPL performance trends (2008–2022)  
- Analyze batting, bowling & team dynamics  
- Study match-winning patterns and toss influence  
- Build a clean & interactive Power BI dashboard  
- Demonstrate ETL + visualization workflow end-to-end  

---

## 🛠 Tools & Technologies

| Category | Tools Used |
|---------|------------|
| **Database** | PostgreSQL |
| **Data Analysis** | Python (Pandas, NumPy, Matplotlib) |
| **Visualization** | Power BI Desktop |
| **ETL** | SQL Queries + Python |
| **Version Control** | Git & GitHub |

---

## 📂 Dataset Description

### **1️⃣ Matches Dataset — `ipl_matches_2008_2022`**
Contains match-level data including:
- Match ID  
- Venue  
- Winner  
- Toss decision  
- Player of the match  
- Result type & margin  

### **2️⃣ Ball-by-Ball Dataset — `ipl_ball_by_ball_2008_2022`**
Contains granular ball-by-ball details:
- Over & ball  
- Bowler, batsman  
- Runs, extras  
- Wicket details  

---

## 🔄 Data Pipeline

### **1️⃣ Python Cleaning**
- Load CSV  
- Clean null values  
- Correct data types  
- Export cleaned dataset  

### **2️⃣ SQL Transformation**
- Import using COPY command  
- Remove duplicates  
- Create analytical views  

### **3️⃣ Power BI Modeling**
- Data relationships  
- DAX measures  
- KPIs and visuals  

### **4️⃣ Dashboard Development**
- Slicers  
- KPIs  
- Charts  
- Performance summaries  

---

## 📁 Project Structure

D:\IPL Power BI Project
│
├── Dashboard
│ └── cricket.pbix
│
├── Dashboard Images
│ └── dashboard.png
│
├── data
│ ├── ipl_ball_by_ball_2008_2022.csv
│ └── ipl_matches_2008_2022.csv
│
└── README.md


---

## 📈 Key Insights from Dashboard

### 🏆 Title Winner
- Gujarat Titans highlighted among recent champions.

### 🥇 Orange Cap Leader
- **Virat Kohli — 6634 runs**

### 🟪 Purple Cap Leader
- **DJ Bravo — 183 wickets**

### 💥 Tournament Totals
- **6s:** 10.66K  
- **4s:** 25.49K  

### 🎯 Batting Stats
- Total runs  
- Strike rate  
- Number of 4s & 6s  

### 🎯 Bowling Stats
- Wickets  
- Economy  
- Bowling average  
- Bowling strike rate  

### 🏟 Venue-wise Match Wins
- Eden Gardens  
- Wankhede Stadium  
- M. Chinnaswamy Stadium  

### 🧭 Toss Decisions
- Field-first strategy gives better win percentages.

### 🥇 Most Successful Team
- **Mumbai Indians — 131 wins**

---

## 📊 Dashboard Features

- ✔ Dropdown selector for batsmen  
- ✔ Dropdown selector for bowlers  
- ✔ Interactive slicers  
- ✔ Donut charts (toss decision)  
- ✔ Venue-wise stacked bar charts  
- ✔ Team performance bar charts  
- ✔ KPI cards for key stats  
- ✔ Clean, modern design  

---

## 🧪 How to Run the Project

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/IPL-Cricket-Analysis.git

2️⃣ Import SQL Data

COPY ipl_matches_2008_2022 
FROM 'path-to-file.csv' 
DELIMITER ',' CSV HEADER;

3️⃣ Run Python Script

python data_cleaning.py

4️⃣ Open Power BI File

Dashboard/cricket.pbix


🚀 Future Enhancements

Machine learning player performance predictions

Streamlit or Power BI Embedded web app

Season-wise comparison pages

Enhanced SQL views for optimization


👨‍💻 Author

Mukesh Kumar
Mining Engineer • MS Environmental Engineering (Italy)
Data Analyst | SQL | Python | Power BI


## 💡 Power BI Skills & Learnings

This project demonstrates proficiency in advanced Data Analytics and Business Intelligence techniques:

* **ETL (Power Query):** Extensive use of Power Query Editor for data cleaning, transformation, and shaping (e.g., merging tables, handling data types, addressing missing values).
* **Advanced Data Modeling:** Implementing an efficient **Star Schema** with well-defined relationships between Fact and Dimension tables for optimal performance.
* **DAX Proficiency:** Creation of complex and optimized DAX measures such as `Total Runs`, `Strike Rate (Adjusted)`, `Economy Rate`, `Rankings`, and `Time Intelligence` functions.
* **Report Design & UX:** Focusing on clean, professional design, effective use of white space, color themes, and implementation of features like **Custom Tooltips** and **Drill-through/Drill-down** capabilities for enhanced user experience.

---

## ⚙️ Local Setup Guide

To explore the Power BI report locally, please ensure you have **Microsoft Power BI Desktop** installed.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/mukeshkd58/IPL_Cricket_Analysis_2008-2022_SQL_Python_Powerbi.git](https://github.com/mukeshkd58/IPL_Cricket_Analysis_2008-2022_SQL_Python_Powerbi.git)
    ```
2.  **Open the File:** Navigate to the `Dashboard/` folder and open the `cricket.pbix` file.
3.  **Explore:** Interact with the dashboard slicers and visuals to analyze the data.

---

## ✍️ Author & Connect

I welcome feedback and collaborations!

| Platform | Link |
| :--- | :--- |
| **Author** | **Mukesh Kumar** |
| **GitHub** | [mukeshkd58](https://github.com/mukeshkd58) |
| **Project URL** | [IPL Cricket Analysis 2008-2022](https://github.com/mukeshkd58/IPL_Cricket_Analysis_2008-2022_SQL_Python_Powerbi) |
| **LinkedIn** | [mukesh-kumar-567284301](https://www.linkedin.com/in/mukesh-kumar-567284301/) |