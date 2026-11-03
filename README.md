# International-Football-Match-Analysis
Developed an interactive Power BI dashboard to analyze international football matches from 1872 to 2026. The project explores team performance, wins and losses, goals scored and conceded, clean sheets, and home vs away trends using DAX measures, Power Query, and data visualization.

# International Football Match Analysis
## Power BI Dashboard – Project Documentation

### 1. Project Overview

The International Football Match Analysis project focuses on analyzing historical international football matches using Microsoft Power BI.

The dashboard provides insights into team performance, match outcomes, goal-scoring patterns, and historical trends. It allows users to explore football statistics interactively through team and tournament filters.

The analysis covers international football matches from 1872 to 2026.

### 2. Project Objectives

The primary objectives are:

- Analyze international football match results.
- Evaluate team performance through wins, losses, and draws.
- Compare goals scored and conceded by teams.
- Understand home and away team performance.
- Calculate important performance indicators.
- Identify historical trends in international football.

### 3. Dataset Description

The project uses historical international football match data.

**Dataset:** International Football Results

**Main fields used:**

| Column | Description |
|---|---|
| date | Date of the match |
| home_team | Home team |
| away_team | Away team |
| home_score | Goals scored by the home team |
| away_score | Goals scored by the away team |
| tournament | Competition or tournament |
| city | Match location |
| country | Host country |
| neutral | Indicates whether the match was played at a neutral venue |

Additional fields were created during data preparation and analysis.

### 4. Tools and Technologies

- **Microsoft Power BI:** Dashboard development and visualization.
- **Power Query:** Data cleaning and transformation.
- **DAX:** Calculated measures and performance indicators.
- **CSV / Excel:** Dataset storage and initial inspection.

### 5. Data Preparation

The dataset was prepared using Power Query and Power BI.

The major data preparation activities included:

1. Checking missing and duplicate records.
2. Standardizing team and tournament names.
3. Converting match dates into the appropriate date format.
4. Ensuring home and away scores were stored as numeric values.
5. Creating a team reference table containing unique team names.
6. Creating calculated columns and measures for match analysis.
7. Establishing appropriate filter behaviour for team and tournament selections.

### 6. Key Performance Indicators (KPIs)

The dashboard contains six primary KPIs.

| KPI | Description |
|---|---|
| Matches Played | Total matches played by the selected team |
| Total Wins | Number of matches won |
| Average Goals Scored | Average goals scored per match |
| Win Ratio | Percentage of matches won |
| Highest Goals | Maximum goals scored by the selected team in a single match |
| Clean Sheets | Matches in which the opponent scored zero goals |

Additional measures developed during the analysis include:

- Total Losses
- Total Draws
- Goals Scored
- Goals Conceded
- Average Goals Conceded
- Goal Difference

### 7. Dashboard Components

The dashboard contains interactive filters, KPI cards, and three main analytical visualizations.

**A. Team and Tournament Filters**

Two dropdown slicers allow users to filter the dashboard by:
- National team
- Tournament

All relevant KPIs and visualizations respond to the selected filters.

**B. Average Goals Comparison**

A clustered column chart compares average goals scored and conceded by the selected team across tournaments.

Purpose:
- Evaluate attacking performance.
- Understand defensive performance.
- Compare scoring and conceding patterns.

**C. Wins, Losses and Draws**

A pie chart displays the distribution of match outcomes for the selected team.

Purpose:
- Understand overall team performance.
- Compare wins, losses, and draws.
- Evaluate the team's competitive record.

**D. Home Wins and Away Wins Over Time**

A line chart compares home and away victories across different years.

Purpose:
- Identify historical performance trends.
- Understand home advantage.
- Compare changes in home and away wins over time.

### 8. Key Analytical Insights

The dashboard enables users to investigate the following:

- The overall winning performance of national teams.
- Differences between goals scored and goals conceded.
- The relationship between home and away victories.
- Changes in international football performance over time.
- Differences in team performance across tournaments.
- Defensive consistency through clean-sheet statistics.

The insights are interactive and depend on the selected team and tournament.

### 9. Future Scope

The project can be extended through:

1. **Goalscorer Analysis:** Integration of a reliable match-level international goalscorer dataset.
2. **Player Performance:** Analysis of individual player goals and international appearances.
3. **Tournament Analysis:** Detailed comparison of team performances across major competitions.
4. **Home Advantage Analysis:** Further investigation of home, away, and neutral venue results.
5. **Predictive Analytics:** Application of statistical and machine learning models to explore match outcomes.
6. **Advanced Time-Series Analysis:** Investigation of long-term team performance trends.

### 10. Conclusion

The International Football Match Analysis project demonstrates how historical football data can be transformed into meaningful insights using Power BI.

Through interactive filters, DAX measures, and visual analytics, the dashboard provides an accessible way to explore international football performance across teams, tournaments, and time periods.

The project also demonstrates practical skills in data cleaning, data modelling, analytical calculations, and dashboard development.

### 11. Skills Demonstrated

- Data Cleaning and Transformation
- Exploratory Data Analysis
- Power Query
- DAX
- Data Modelling
- Data Visualization
- KPI Development
- Interactive Dashboard Design
- Analytical Thinking

**Project Outcome:** Developed an interactive one-page Power BI dashboard for analyzing historical international football match performance from 1872 to 2026.
