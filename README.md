**ICC T20 2022 Men's World Cup Analytics**

This repository contains an analytics project on the ICC T20 2022 Men's World Cup, created using **Python** and **Power BI**. 
The project demonstrates data transformation, analysis, and dashboard creation for insights into player and team performances.

Project Overview
The project aims to analyze player performances and team dynamics during the ICC T20 2022 Men's World Cup, focusing on categories like power hitters, anchors, 
all-rounders, and bowlers. A comprehensive dashboard in **Power BI** highlights key insights.

**Data Workflow**
1. **Data Preparation (Python)**:
The project begins by converting JSON data into CSV files using Python in a Jupyter Notebook.
Files processed:
dim_players.json
fact_batting_summary.json
fact_bowling_summary.json
fact_wc_match_result.json
These JSON files were saved as CSV files on the desktop for further processing.
2. **Data Transformation (Power BI - Power Query)**:
The CSV files were imported into **Power BI**.
Data was cleaned, transformed, and structured using **Power Query**.
Key steps included removing duplicates, handling missing values, and creating relationships between tables.
3. **Calculations (DAX Formulas)**:
Created calculated columns and measures using DAX to derive insights.
Examples: Strike Rate, Economy Rate, Batting Average, Boundary%, Dot Ball% etc.
4. **Dashboard Creation**:
A dynamic Power BI dashboard was built to visualize insights from the data.

Dashboard Details
Category 1: **Player Analysis**
Analyzes player performance and categorizes them into the following sections:

**Power Hitters**: Players with high strike rates and boundary rates.
**Anchors**: Consistent batters with stable performances.
**Finishers**: Players excelling in high-pressure situations.
**All-Rounders**: Players contributing significantly with both bat and ball.
**Fast Bowlers**: Bowlers specializing in pace and wicket-taking ability.


Category 2: **Final 12**
A hypothetical Final 12 was created based on player performances across all sections in Player Analysis.

**Tools and Technologies**
**Python**: Data extraction and conversion of JSON to CSV.
**Power BI**: Data transformation (Power Query), calculated columns and measures (DAX), and dashboard creation.

**Jupyter Notebook**:
The Python scripts for JSON-to-CSV conversion are in the notebooks folder.

**Power BI Dashboard**:
Open the .pbix file in Power BI Desktop to explore the visualizations.

**Insights Gained**
- Identified top-performing players in different roles.
- Derived a hypothetical Final 12 based on comprehensive player analysis.
- Visualized team performance trends throughout the tournament.

**Future Scope**
Expand the analysis to include comparative trends across multiple ICC tournaments.
Incorporate additional performance metrics like fielding stats or player impact scores.
