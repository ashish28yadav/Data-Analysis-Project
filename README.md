---
title: T20 World Cup Cricket Data Analysis
---

# 🏏 T20 World Cup Cricket Data Analysis Project

## 📌 Project Overview
This project performs an in-depth analysis of **T20 World Cup cricket data** using a combination of **Python**, **Power BI**, and **DAX**. It provides statistical insights into match results, player performances, and team metrics, aimed at generating interactive dashboards and informed cricketing decisions.

---

## 🎯 Project Objectives
- Collect and clean T20 World Cup match and player data
- Analyze match outcomes, team performance, and player statistics
- Visualize insights using Power BI dashboards
- Generate a data-driven **Best Playing XI**
- Create custom **DAX formulas** for advanced cricket metrics
- Enable scalable and reproducible analytics workflows

---

## 🛠️ Tools & Technologies Used

| Category        | Tools / Languages         |
|----------------|---------------------------|
| Programming     | Python 3.x                |
| Visualization   | Power BI Desktop          |
| Data Modeling   | DAX, Power Query          |
| Documentation   | Excel, PDF                |
| Libraries       | `pandas`, `json`, others  |

---

## 📂 Project Structure

├── Cricket Best 11.pbix
├── t20_cric_1_power_query.pbix
├── Stage-2.pbix
├── Stage-3.pbix
├── t20_data_preprocessing.ipynb
├── t20_json_files.zip
├── t20_csv_files.zip
├── web_scrapping_codes.zip
├── DAX Measures and Calculated columns.xlsx
└── Parameter Scoping.pdf


---

## 📈 Major Insights & Features

### Match Analysis
- Match-wise summaries
- Win margins, venue stats, and winning trends

### Player Analysis
- Top batsmen and bowlers by format
- All-rounder ranking system
- Historical performance comparisons

### Team Analysis
- Head-to-head comparisons
- Tournament progression patterns
- Win strategies and tactics

### Best XI Selection
- Data-driven selection using batting/bowling stats
- Context-aware ranking for ideal team composition

---


---

## 📥 Data Sources
- Match records from official T20 World Cup sources
- Player statistics scraped and structured via Python scripts
- Venue-specific performance data
- JSON (raw) and CSV (cleaned) formats

---

## 🔧 Data Processing Workflow

### Step 1: Data Collection
- Web scraping via Python (`web_scrapping_codes.zip`)
- Raw JSON datasets

### Step 2: Preprocessing
- Run `t20_data_preprocessing.ipynb` for:
  - Cleaning
  - Feature engineering
  - CSV export

### Step 3: Power BI Dashboards
- Use `.pbix` files for visual exploration:
  - `Cricket Best 11.pbix`
  - `Stage-2.pbix`
  - `Stage-3.pbix`

### Step 4: DAX Implementation
- Refer to `DAX Measures and Calculated columns.xlsx` for:
  - Custom metrics
  - Calculated columns
  - KPIs

---

## 📈 Visualizations

All Power BI dashboards were created with an emphasis on:
- Clarity and accessibility
- KPI alignment
- Interactive filtering for teams, players, and venues

### ✅ Visualization Objectives:
1. **Match Summary Dashboards**  
   - Win/loss breakdowns  
   - Toss effect  
   - Victory margins  

2. **Player Performance Charts**  
   - Top batsmen and bowlers  
   - All-rounder consistency  
   - Strike rate and economy rate filters  

3. **Team vs Team Comparisons**  
   - Head-to-head win ratios  
   - Tournament journey tracking  

4. **Best XI Selection**  
   - Metric-based selection  
   - Batting vs bowling balance  

5. **Venue Analysis**  
   - Win % by location  
   - Pitch performance  

All visualizations were built using **Power BI** and labeled with filters and legends for user interactivity.

---

## 🌐 Upload to GitHub

This repository includes:
- Power BI `.pbix` files (`Stage-3.pbix`, `Cricket Best 11.pbix`)
- Source code for scraping and preprocessing (`.ipynb`, `.zip`)
- Cleaned and raw datasets (`.csv`, `.json`)
- DAX formulas (`.xlsx`)
- This interactive README documentation

✅ **To interact with the visualizations:**
1. Clone/download this repo
2. Open `.pbix` files in **Power BI Desktop**
3. Use the slicers and filters to explore various metrics
4. Review the **README** and `Parameter Scoping.pdf` for logic behind dashboards

---

## ⚙️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/<your-username>/t20-worldcup-analysis.git

# Install Python dependencies
pip install pandas json
Then:

Open t20_data_preprocessing.ipynb in Jupyter

Run preprocessing steps to regenerate .csv files (optional)

Launch .pbix files in Power BI Desktop

🧪 Parameter Configuration
Refer to Parameter Scoping.pdf for:

Filters (overs, strike rates, wickets)

Thresholds for inclusion

Custom metrics definitions

🔮 Future Enhancements
Real-time API integration for live matches

Predictive analytics (e.g., win probability)

Player form trajectory dashboards

Tournament evolution across years
