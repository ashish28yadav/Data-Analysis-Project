# 🏏 T20 World Cup Cricket Data Analysis

## 📌 Overview
Cricket, especially in the T20 format, has evolved into a highly data-driven sport where team strategies, player performances, and match outcomes are deeply analyzed. This project focuses on extracting meaningful insights from T20 World Cup cricket data using **Python**, **Power BI**, and **DAX**.

The project transforms raw JSON cricket datasets into structured analytical dashboards that help evaluate player performance, compare teams, analyze venues, and generate a data-driven **Best Playing XI**.

---

## 🖼 Dashboard Screenshots

### 📌 Match Summary Dashboard
![Match Dashboard](https://github.com/user-attachments/assets/63c06924-a628-4705-9ae8-1de1f0a83aa4)

---

### 📌 Player Performance Dashboard
![Player Dashboard](https://github.com/user-attachments/assets/b5132b70-a099-4685-bc52-b4dc8c004173)

---

### 📌 Best XI Dashboard
![Best XI Dashboard](https://github.com/user-attachments/assets/3323ea23-3999-4bc7-9dc3-1eba3088d80f)

---

### 📌 Venue Analysis Dashboard
![Venue Dashboard](https://github.com/user-attachments/assets/b8e3a1a3-75e3-4bc5-83a0-0cea4fced573)

---

# 🎯 Objectives

- Clean and preprocess raw cricket match datasets
- Analyze player and team performances
- Build interactive Power BI dashboards
- Create advanced DAX measures and KPIs
- Generate a data-driven Best Playing XI
- Provide actionable cricket insights using analytics

---

# ❓ Problem Statement

The International Cricket Board and cricket analysts require a comprehensive analytics solution to make data-backed decisions during T20 World Cup tournaments.

The project aims to:
- Process historical T20 World Cup data
- Visualize key cricket metrics
- Evaluate players using custom performance logic
- Identify optimal team combinations
- Enable strategic analysis through dashboards

---

# 📖 Data Dictionary

| Variable | Description |
|----------|-------------|
| `Match_ID` | Unique match identifier |
| `Team1`, `Team2` | Teams participating in the match |
| `Winner` | Winning team |
| `Player_of_the_Match` | Best player of the match |
| `Runs`, `Wickets` | Match and player contributions |
| `Venue` | Match venue |
| `Date` | Match date |
| `Player Stats` | Runs, strike rate, wickets, economy |
| `All-Rounder Index` | Custom metric for all-rounders |
| `Head-to-Head` | Historical team matchup data |
| `Venue Win %` | Team success rate by venue |
| `Batting/Bowling Rank` | Weighted performance metrics |

---

# 🛠 Tools & Technologies

| Category | Technologies |
|----------|--------------|
| Programming | Python 3.x |
| Visualization | Power BI Desktop |
| Data Modeling | Power Query, DAX |
| Libraries | pandas, json |
| Documentation | Excel, PDF |

---

# 🚀 Workflow

## 1️⃣ Data Collection
- Raw cricket data collected in JSON format
- Web scraping performed using Python scripts

## 2️⃣ Data Preprocessing
- JSON files cleaned and transformed into CSV
- Missing values handled
- Data standardized for analysis

## 3️⃣ Data Modeling
- Relationships created in Power BI
- Fact and dimension tables structured

## 4️⃣ Dashboard Development
Interactive dashboards created for:
- Match summaries
- Player performances
- Team comparisons
- Venue analysis
- Best XI selection

## 5️⃣ KPI & DAX Development
Custom DAX measures created for:
- Strike Rate
- Batting Average
- Economy Rate
- All-Rounder Index
- Team Win Percentage
- Player Rankings

---

# 📊 Key Dashboards & Insights

## 🏏 Match Summary Dashboard
- Toss impact analysis
- Match outcome trends
- Victory margin analysis
- Venue-wise performance

---

## 👤 Player Performance Dashboard
- Top batsmen and bowlers
- Strike rate analysis
- Economy rate comparison
- Consistency filters

---

## 🤝 Team Comparison Dashboard
- Head-to-head analysis
- Team win trends
- Tournament progression
- Comparative statistics

---

## ⭐ Best Playing XI Dashboard
- Metric-based player selection
- Balanced squad generation
- Role-specific optimization
- Performance-weighted ranking system

---

## 🏟 Venue Analysis Dashboard
- Win percentage by stadium
- Pitch performance trends
- Venue impact analysis

---

# 📂 Repository Structure

```python
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
├── Parameter Scoping.pdf
└── README.md
```

---

# ⚙️ Installation & Setup

## Clone the Repository

```bash
git clone https://github.com/<your-username>/t20-worldcup-analysis.git
```

---

## Install Required Libraries

```bash
pip install pandas json
```

---

# ▶️ How to Run the Project

1. Open `t20_data_preprocessing.ipynb`
2. Run all notebook cells
3. Generate cleaned CSV files
4. Open `.pbix` files in Power BI Desktop
5. Explore dashboards using slicers and filters

---

# 📈 Features

- Interactive Power BI dashboards
- Advanced DAX KPIs
- Dynamic filters and slicers
- Best XI recommendation system
- Venue-based analytics
- Team and player comparisons

---

# 🔮 Future Enhancements

- Real-time live match integration
- Predictive analytics using Machine Learning
- Win probability prediction
- Historical World Cup comparison dashboards
- Web deployment using Streamlit

---

# 📚 Learning Outcomes

Through this project, the following concepts were implemented:

- Data Cleaning & Transformation
- Exploratory Data Analysis
- Power BI Dashboard Design
- DAX Calculations
- Sports Analytics
- Data Visualization
- Performance Optimization

---

# ✅ Conclusion

This project demonstrates how cricket analytics can be transformed into actionable insights using Python and Power BI. By leveraging structured data modeling, DAX calculations, and interactive visualizations, the project enables deeper understanding of T20 World Cup performances and strategic team decision-making.

---

# 👨‍💻 Author

**Ashish Ranjan**

- Software Engineer
- Data Analytics & App Development Enthusiast
- Skilled in Python, Java, Power BI, and Mobile Development

---
