# T20 World Cup Cricket Data Analysis Project

## Project Overview
This project performs an in-depth analysis of T20 World Cup cricket data using various tools and technologies including Python, Power BI, and DAX. The analysis includes match results, player performances, and detailed statistical insights from T20 World Cup matches.

## Project Structure
├── Cricket Best 11.pbix # Power BI dashboard for best playing XI analysis
├── web_scrapping_codes.zip # Web scraping scripts for data collection
├── t20_json_files.zip # Raw data in JSON format
├── t20_csv_files.zip # Processed data in CSV format
├── t20_data_preprocessing.ipynb # Jupyter notebook for data preprocessing
├── t20_cric_1_power_query.pbix # Initial Power BI analysis with Power Query
├── Stage-2.pbix # Second stage of Power BI analysis
├── Stage-3.pbix # Final stage of Power BI analysis
├── Parameter Scoping.pdf # Documentation for parameter configurations
└── DAX Measures and Calculated columns.xlsx # DAX formulas and calculations

## Data Processing Workflow

### 1. Data Collection
- Data was collected through web scraping (available in `web_scrapping_codes.zip`)
- Raw data stored in JSON format (`t20_json_files.zip`)

### 2. Data Preprocessing
The `t20_data_preprocessing.ipynb` notebook contains the following steps:
- Data cleaning and transformation
- Match results processing
- Player statistics calculation
- Data validation and quality checks
- Export to CSV format for visualization

### 3. Power BI Analysis
The project includes multiple Power BI files for different aspects of analysis:

1. **Cricket Best 11.pbix**
   - Analysis for selecting the best playing XI
   - Player performance metrics
   - Team statistics

2. **t20_cric_1_power_query.pbix**
   - Initial data transformation using Power Query
   - Basic visualizations and insights

3. **Stage-2.pbix & Stage-3.pbix**
   - Progressive development of advanced analytics
   - Complex visualizations
   - Performance metrics and KPIs

### 4. DAX Implementation
The `DAX Measures and Calculated columns.xlsx` file contains:
- Custom DAX measures for cricket-specific calculations
- Calculated columns for derived metrics
- Performance indicators and statistical formulas

## Key Features

1. **Match Analysis**
   - Detailed match results and statistics
   - Team performance metrics
   - Ground-wise analysis
   - Win margins and patterns

2. **Player Performance Analysis**
   - Batting statistics
   - Bowling figures
   - All-rounder performance metrics
   - Player rankings and comparisons

3. **Team Statistics**
   - Team-wise performance analysis
   - Head-to-head comparisons
   - Tournament progression tracking
   - Victory patterns and strategies

## Technical Stack

1. **Programming Languages & Tools**
   - Python (Data Preprocessing)
   - Power BI (Visualization and Analysis)
   - DAX (Custom Calculations)
   - Power Query (Data Transformation)

2. **Libraries Used**
   - Pandas (Data manipulation)
   - JSON (Data parsing)
   - Other Python libraries for data processing

## Data Sources
- Match results and statistics
- Player performance data
- Tournament-specific information
- Ground and venue details

## Visualization Outputs
The project includes various visualizations such as:
- Match summary dashboards
- Player performance charts
- Team comparison visualizations
- Tournament statistics
- Best XI selection metrics

## Parameter Configuration
Refer to `Parameter Scoping.pdf` for detailed information about:
- Analysis parameters
- Calculation thresholds
- Filtering criteria
- Performance metrics

## Future Enhancements
Potential areas for project expansion:
1. Real-time data integration
2. Advanced predictive analytics
3. Player form trajectory analysis
4. Historical tournament comparisons

## Usage Instructions
1. Start with the preprocessing notebook (`t20_data_preprocessing.ipynb`)
2. Review the processed data in CSV format
3. Open Power BI files in sequence for progressive analysis
4. Refer to DAX measures file for calculation details

## Dependencies
- Python 3.x
- Power BI Desktop
- Required Python libraries (pandas, json)
- Microsoft Excel (for DAX measures reference)
