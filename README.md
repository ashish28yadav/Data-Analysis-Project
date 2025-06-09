# 🏏 T20 World Cup Cricket Data Analysis

## 📌 Context
Cricket, especially in its T20 format, has become a high-stakes, data-driven sport where team strategies, player performances, and match outcomes are closely scrutinized. With growing reliance on analytics, stakeholders such as coaches, analysts, and fans are seeking deeper insights into the game using historical match data.

This project focuses on T20 World Cup tournaments and aims to convert raw and structured cricket data into meaningful visual insights. Using data science techniques, it enables informed decision-making in areas like team selection, player evaluation, and match strategy.

---

## ❓ Problem Statement
The International Cricket Board and team analysts want to make data-backed decisions to improve on-field performance during the T20 World Cup. The objective is to build an end-to-end analytics solution that preprocesses and models match and player data, creates interactive dashboards, and provides actionable insights — including an optimal **Best Playing XI**.

---

## 🎯 Objective
Build a comprehensive data analysis and visualization project to:

- Clean and preprocess match and player data
- Analyze matches, players, and team performances across tournaments
- Visualize key cricket metrics and insights using Power BI dashboards
- Generate a data-driven "Best XI" using custom cricket logic
- Implement DAX for advanced cricket KPIs and performance filters

---

## 🧾 Data Dictionary

| Variable     | Description |
|--------------|-------------|
| `Match_ID`   | Unique identifier for each match |
| `Team1`, `Team2` | Teams playing the match |
| `Winner`     | Match winner |
| `Player_of_the_Match` | Best performer |
| `Runs`, `Wickets` | Team and player contributions |
| `Venue`      | Match location |
| `Date`       | Match date |
| `Player Stats` | Includes runs, strike rate, wickets, economy |
| `All-Rounder Index` | Custom metric for dual-role players |
| `Head-to-Head` | Historical matchup results |
| `Venue Win %` | Team success rate by venue |
| `Batting/Bowling Rank` | Weighted metric for performance |

---

## ✅ Final Results

To complete this project:

- 🔍 **Python** was used to scrape, clean, and preprocess the raw JSON data into structured CSV format.
- 📊 **Power BI** was used to create interactive dashboards.
- 🧮 **DAX** measures were developed for performance metrics, KPIs, and Best XI logic.
- 📈 Visuals allow filtering by **team**, **venue**, **player**, and **match details**.

### Key Deliverables

- Cleaned Datasets: `.csv` and `.json`  
- Power BI Dashboards: `Cricket Best 11.pbix`, `Stage-2.pbix`, `Stage-3.pbix`  
- DAX Metrics File: `DAX Measures.xlsx`  
- Parameter Guide: `Parameter Scoping.pdf`  
- Web Scraping Code: `web_scrapping_codes.zip`  
- Preprocessing Notebook: `t20_data_preprocessing.ipynb`

---

## 🧰 Tools & Technologies

| Category       | Tools / Technologies         |
|----------------|------------------------------|
| Programming     | Python 3.x                   |
| Visualization   | Power BI Desktop             |
| Data Modeling   | Power Query, DAX             |
| Libraries       | pandas, json                 |
| Documentation   | Excel, PDF                   |

---

## ⚙️ Setup Instructions

```bash
# Clone the repository
git clone https://github.com/<your-username>/t20-worldcup-analysis.git

# Install Python dependencies
pip install pandas json
Then:

Open t20_data_preprocessing.ipynb in Jupyter Notebook

Run all cells to generate cleaned CSV files

Open .pbix files in Power BI Desktop

Refer to Parameter Scoping.pdf for logic and filters

Explore DAX KPIs in DAX Measures.xlsx

📊 Key Visual Insights
🏆 Match Summary Dashboards
Toss impact

Victory margins

Match outcomes by venue

👤 Player Performance Dashboards
Top batsmen and bowlers

Consistency filters (SR, Economy)

All-rounder analysis

🔄 Team Comparison Dashboards
Head-to-head records

Win trends

Tournament progress

🧢 Best XI Selection
Context-aware metric-based selection

Balanced team roles (batting, bowling, all-rounders)

🏟️ Venue Analysis
Win % by stadium

Pitch performance by team

🔮 Future Enhancements
Real-time API integration for live match data

Predictive analytics (e.g., win probability, performance forecasting)

Historical evolution dashboards for multiple T20 World Cup editions

📁 Repository Structure
python
Copy
Edit
t20-worldcup-analysis/
├── Cricket Best 11.pbix
├── Stage-2.pbix
├── Stage-3.pbix
├── t20_cric_1_power_query.pbix
├── t20_data_preprocessing.ipynb
├── t20_json_files.zip
├── t20_csv_files.zip
├── web_scrapping_codes.zip
├── DAX Measures and Calculated columns.xlsx
└── Parameter Scoping.pdf
🚀 How to Explore the Visuals
Clone/download the repository

Open the .pbix files using Power BI Desktop

Use slicers and filters for insights across teams, players, venues, and match phases

Refer to the documentation PDFs for deeper understanding
