🏏 T20 World Cup Cricket Data Analysis Project
📌 Project Overview
This project performs an in-depth analysis of T20 World Cup cricket data using a combination of Python, Power BI, and DAX. It provides statistical insights into match results, player performances, and team metrics, aimed at generating interactive dashboards and informed cricketing decisions.

🎯 Project Objectives
Collect and clean T20 World Cup match and player data

Analyze match outcomes, team performance, and player statistics

Visualize insights using Power BI dashboards

Generate a data-driven Best Playing XI

Create custom DAX formulas for advanced cricket metrics

Enable scalable and reproducible analytics workflows

🛠️ Tools & Technologies Used
Category	Tools / Languages
Programming	Python 3.x
Visualization	Power BI Desktop
Data Modeling	DAX, Power Query
Documentation	Excel, PDF
Libraries	pandas, json, others

📂 Project Structure
python
Copy
Edit
├── Cricket Best 11.pbix                  # Power BI dashboard for best playing XI
├── t20_cric_1_power_query.pbix           # Power BI with Power Query analysis
├── Stage-2.pbix                          # Intermediate Power BI analytics
├── Stage-3.pbix                          # Final, refined Power BI analytics
├── t20_data_preprocessing.ipynb          # Jupyter notebook for data preprocessing
├── t20_json_files.zip                    # Raw JSON data
├── t20_csv_files.zip                     # Cleaned and processed CSV data
├── web_scrapping_codes.zip               # Python scripts for data scraping
├── DAX Measures and Calculated columns.xlsx  # Custom DAX calculations
├── Parameter Scoping.pdf                 # Parameter configuration reference
📈 Major Insights & Features
Match Analysis
Match-wise summaries

Win margins, venue stats, and winning trends

Player Analysis
Top batsmen and bowlers by format

All-rounder ranking system

Historical performance comparisons

Team Analysis
Head-to-head comparisons

Tournament progression patterns

Win strategies and tactics

Best XI Selection
Data-driven selection using batting/bowling stats

Context-aware ranking for ideal team composition

📥 Data Sources
Official T20 World Cup match reports

Player statistics via web scraping

Venue and ground metadata

JSON format (raw) and CSV format (processed)

🔧 Data Processing Workflow
1. Data Collection
Web scraping scripts (web_scrapping_codes.zip)

JSON files of raw match data

2. Data Preprocessing
Run t20_data_preprocessing.ipynb

Includes data cleaning, validation, and export to CSV

3. Power BI Visualizations
Load CSVs into Power BI files:

t20_cric_1_power_query.pbix for early exploration

Stage-2.pbix for detailed metrics

Stage-3.pbix for final dashboards

4. DAX Implementation
Refer to DAX Measures and Calculated columns.xlsx for:

Custom cricket metrics

Advanced performance KPIs

Calculated columns

⚙️ Setup Instructions
Clone or download the repository.

Install Python 3.x and the following packages:

bash
Copy
Edit
pip install pandas
Run t20_data_preprocessing.ipynb to generate CSVs.

Open .pbix files in Power BI Desktop.

Use Excel to review DAX measures (if modifying or expanding).

📊 Visualization Samples
Match dashboards with win/loss stats

Player cards with batting/bowling graphs

Team heatmaps

Best XI radar charts

⚙️ Parameter Configuration
Defined in Parameter Scoping.pdf:

Thresholds for performance inclusion

Metrics for best player/team selection

Filters for match conditions

🔮 Future Enhancements
Integrate live match APIs

Predictive modeling using player trends

Compare historical vs current tournaments

Expand to include ODI or Test World Cups

