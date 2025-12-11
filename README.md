# 📊 IPL Cricket Analysis (2008–2022)
### _SQL • Python • Power BI — End-to-End Data Analytics Project_

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
12. [Power BI Skills & Learnings](#-power-bi-skills--learnings)
13. [Local Setup Guide](#-local-setup-guide)
14. [Author & Connect](#-author--connect)

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
Contains match-level data:
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
- Import using COPY  
- Remove duplicates  
- Create analytical views  

### **3️⃣ Power BI Modeling**
- Build relationships  
- Create DAX measures  
- Develop KPIs  

### **4️⃣ Dashboard Development**
- Slicers  
- KPIs  
- Charts  
- Performance summaries  

---

## 📁 Project Structure

IPL Power BI Project
│
├── dashboard
│   └── cricket.pbix
│
├── dashboard images
│   └── dashboard.png
│
├── IPL images
│   └── [other IPL-related images]
│
├── data
│   ├── ipl_ball_by_ball_2008_2022.csv
│   └── ipl_matches_2008_2022.csv
│
├── sql
│   └── [SQL scripts & queries]
│
├── .gitignore
├── IPL Cricket Analysis.pdf
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
- Runs, Strike Rate, 4s & 6s  

### 🎯 Bowling Stats
- Wickets, Economy, Bowling Avg, Strike Rate  

### 🏟 Venue-Wise Wins
- Eden Gardens  
- Wankhede Stadium  
- Chinnaswamy Stadium  

### 🧭 Toss Decisions
- Field-first strategy shows higher win %.

### 🥇 Most Successful Team
- **Mumbai Indians — 131 wins**

---

## 📊 Dashboard Features

- ✔ Dropdown for batsmen & bowlers  
- ✔ Interactive slicers  
- ✔ Donut charts (toss decision)  
- ✔ Venue-wise bar charts  
- ✔ Team performance bars  
- ✔ KPI cards  
- ✔ Clean UI/UX  

---

## 🧪 How to Run the Project

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/mukeshkd58/IPL-Cricket-Analysis.git

2️⃣ Import SQL Data

COPY ipl_matches_2008_2022 
FROM 'your-path.csv' 
DELIMITER ',' CSV HEADER;

3️⃣ Run Python Script

python data_cleaning.py

4️⃣ Open Power BI Dashboard

Dashboard/cricket.pbix


🚀 Future Enhancements

Machine learning: Player performance prediction

Streamlit/Power BI Embedded web app

Season-wise comparison pages

More SQL views for analysis

👨‍💻 Author

Mukesh Kumar
Mining Engineer • MS Environmental Engineering (Italy)
Data Analyst | SQL | Python | Power BI

💡 Power BI Skills & Learnings

This project demonstrates strong expertise in:

ETL with Power Query

Star Schema Data Modeling

Advanced DAX Measures

Custom Tooltips & Drill-through Navigation

Professional Dashboard UI/UX


⚙️ Local Setup Guide

Install Power BI Desktop

Clone repo:
git clone https://github.com/mukeshkd58/IPL_Cricket_Analysis_2008-2022_SQL_Python_Powerbi.git

Open Dashboard/cricket.pbix

Explore the dashboard

✍️ Author & Connect

I welcome collaborations and feedback!

Platform	Link
Author	Mukesh Kumar
GitHub	https://github.com/mukeshkd58

Project URL	https://github.com/mukeshkd58/IPL_Cricket_Analysis_2008-2022_SQL_Python_Powerbi

LinkedIn	https://www.linkedin.com/in/mukesh-kumar-567284301/

---# IPL_Cricket_Analysis_sql_Python_PowerBi
# IPL_Cricket_Analysis_sql_Python_PowerBi
