---
title: T20 World Cup Cricket Data Analysis
---

# 🏏 T20 World Cup Cricket Data Analysis Project

Context
Cricket, especially in its T20 format, has become a high-stakes, data-driven sport where team strategies, player performances, and match outcomes are closely scrutinized. With growing reliance on analytics, stakeholders such as coaches, analysts, and fans are seeking deeper insights into the game using historical match data.

This project focuses on T20 World Cup tournaments and aims to convert raw and structured cricket data into meaningful visual insights. Using data science techniques, this project enables informed decision-making in areas like team selection, player evaluation, and match strategy.

Problem Statement
The International Cricket Board and team analysts want to make data-backed decisions to improve on-field performance during the T20 World Cup. The objective is to build an end-to-end analytics solution that preprocesses and models match and player data, creates interactive dashboards, and provides actionable insights — including an optimal "Best Playing XI".

Objective
Build a comprehensive data analysis and visualization project to:

Clean and preprocess match and player data

Analyze matches, players, and team performances across tournaments

Visualize key cricket metrics and insights using Power BI dashboards

Generate a data-driven "Best XI" using custom cricket logic

Implement DAX for advanced cricket KPIs and performance filters

Data Dictionary
The dataset contains match records, player stats, and team performance information across T20 World Cup editions.

Key Variables:

Match_ID: Unique identifier for each match

Team1, Team2: Teams playing the match

Winner: Match winner

Player_of_the_Match: Best performer

Runs, Wickets: Team and player contributions

Venue: Stadium where the match was played

Date: Match date

Player Stats: Runs, Strike Rate, Wickets, Economy Rate

All-Rounder Index: Custom metric for dual-role players

Head-to-Head: Historical results between two teams

Venue Win %: Team performance by location

Batting/Bowling Rank: Composite metrics for player evaluation

Final Results
To complete this project:

Python was used to collect and preprocess data (scraping and cleaning via .ipynb scripts)

Cleaned .csv and .json datasets were visualized using Power BI Desktop

Custom DAX measures were written to calculate metrics like All-Rounder Index, Venue Advantage, and Best XI selection logic

Interactive dashboards were built to allow filtering by team, player, match, and venue

Key Deliverables:

🧹 Cleaned and processed datasets (CSV/JSON)

📊 Power BI Dashboards (Cricket Best 11.pbix, Stage-2.pbix, Stage-3.pbix)

🧮 DAX formulas for cricket KPIs (DAX Measures.xlsx)

🧾 Documentation (Parameter Scoping.pdf)

💡 Best Playing XI selected using weighted cricket metrics

Tools and Technologies
Category	Tools / Technologies
Programming	Python 3.x
Visualization	Power BI Desktop
Data Modeling	Power Query, DAX
Libraries	pandas, json
Documentation	Excel, PDF

Setup Instructions
Clone the GitHub repository:
git clone https://github.com/<your-username>/t20-worldcup-analysis.git

Install Python dependencies:
pip install pandas json

Run preprocessing:

Open t20_data_preprocessing.ipynb

Execute the cleaning steps to regenerate CSVs

Open .pbix files in Power BI to explore dashboards

Refer to Parameter Scoping.pdf and DAX Measures.xlsx for logic and custom metric configuration

Key Visual Insights
✅ Match Summary Dashboards

Toss impact

Victory margins

Match outcomes by venue

✅ Player Performance Dashboards

Top batsmen and bowlers

Consistency filters (SR, Economy)

All-rounder analysis

✅ Team Comparison Dashboards

Head-to-head records

Win trends

Progression through stages

✅ Best XI Selection

Context-aware metric-based selection

Role-based balance (batting, bowling, all-rounders)

✅ Venue Analysis

Pitch behavior

Team-specific win rates by location

Future Enhancements
Live match API integration

Predictive modeling (win probabilities, player form forecasts)

Longitudinal team evolution insights across World Cup editions
