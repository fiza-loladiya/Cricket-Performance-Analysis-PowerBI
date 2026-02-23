# 🏏 Cricket Performance Analysis (Power BI + Web Data)

Turning raw web data into a clean, interactive cricket analysis dashboard in **Power BI**.  
In this project, I pulled real-world stats from **ESPN Statsguru**, cleaned and shaped the data in **Power Query**, created **DAX measures**, and built a 3-page dashboard to analyze **Batting, Bowling, and Fielding** performance by player and career span. 

---

## 📌 Project Overview
**Goal:** Make cricket performance stats easy to explore and compare using an analyst-friendly dashboard.  
**Key idea:** Real web data is messy → Power Query + DAX turns it into something usable and decision-friendly.

---

## 🧩 Dashboard Pages
This report contains **3 analysis pages**, each with a **Player slicer** and **Span (career years)** selection.

### 1) Batting Data Analysis
Key KPIs shown:
- Runs, Innings, Matches, Balls Faced
- Average, Strike Rate
- Centuries, Half-Centuries, 4s, 6s, Zeros, Not Outs

*(Example shown in report: BC Lara (WI), 1992–2007)*

### 2) Bowling Data Analysis
Key KPIs shown:
- Wickets, Overs, Maidens, Runs
- Economy, Average, Strike Rate
- Best Bowling (Innings), 4W / 5W hauls

*(Example shown in report: Abdul Razzaq (PAK), 1998–2010)*

### 3) Fielding Data Analysis
Key KPIs shown:
- Matches, Innings, Total Dismissals
- Catches (Fielder / Wicketkeeper), Stumpings
- Dismissals per innings

*(Example shown in report: A Jadeja, 1992–2000)*

---

## 🌐 Data Source
- **ESPN Cricinfo Statsguru** (web-based stats tables)

**What made it challenging (and fun):**
- Web tables aren’t always consistent
- Data cleaning required careful handling of types, blanks, and formatting
- Some stats needed transformation before they were usable in visuals

---

## 🔧 Workflow (What I Did)
1. **Extracted** player stats from the web (Statsguru tables)
2. **Cleaned & transformed** data in **Power Query**
   - Fixed data types
   - Handled missing values
   - Standardized columns for analysis
3. **Created measures in DAX**
   - KPIs like Runs, Avg, SR, Wickets, Economy, Dismissals, etc.
4. **Built an interactive dashboard**
   - Player selection + span filtering
   - Clean KPI layout for quick scanning

---

## 🧠 Skills Used
- Power BI (data modeling + dashboard design)
- Power Query (web data extraction + cleaning)
- DAX (measures/KPIs)
- Data storytelling & KPI-focused UI
