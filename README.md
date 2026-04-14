

# NFL Quarterback Performance Analysis (2025 Season)

## Overview

This project analyzes quarterback performance from the **2025 NFL regular season** using Python. The primary objective is to compare league-wide quarterback statistics and evaluate how **Jayden Daniels** and **Marcus Mariota** performed relative to each other and to league averages.

The workflow includes data cleaning, feature engineering, statistical ranking, and exporting structured datasets for visualization in Power BI.

---

## Goals

This analysis answers the following questions:

* How did Jayden Daniels perform compared to Marcus Mariota?
* Where do both quarterbacks rank among all NFL quarterbacks?
* How do their statistics compare to league averages?
* Which efficiency metrics best explain performance differences?

---

## Technologies Used

* Python
* Pandas
* CSV data processing
* Power BI (dashboard visualization)

---

## Project Structure

```
NFL-QB-Analysis/
│
├── qb_analysis.py
├── qb_2025.csv
├── qb_cleaned_full.csv
├── daniels_vs_mariota.csv
├── vs_league_average.csv
├── top_10_qbs.csv
└── README.md
```

---

## Dataset

The dataset contains quarterback passing statistics from the **2025 NFL season**, including:

* Passing yards
* Touchdowns
* Interceptions
* Completion percentage
* Passer rating
* Attempts and completions
* Games played
* Efficiency metrics

Source: Pro-Football-Reference

---

## Data Processing Pipeline

The Python script performs the following steps:

### 1. Data Cleaning

* Filters only quarterbacks
* Removes duplicate multi-team player entries
* Removes summary rows (league averages)
* Converts statistical columns into numeric format
  
---

### 3. Ranking Metrics

Quarterbacks are ranked by:

* Passing yards
* Touchdowns
* Passer rating
* TD/INT ratio

This provides league-wide performance context.

---
# League-Level Analysis

Calculated:

* Average passing yards
* Average touchdowns
* Average interceptions
* Average passer rating
* Average efficiency benchmarks

---

## Player Comparison

Direct comparison between:

* Jayden Daniels
* Marcus Mariota

Across:

* Passing yards
* Touchdowns
* Interceptions
* Passer rating
* TD/INT ratio
* Yards per game
* League rankings

---

## Output Files

The script exports several CSV files for further analysis and visualization:

| File                   | Description                          |
| ---------------------- | ------------------------------------ |
| qb_cleaned_full.csv    | Cleaned dataset of all quarterbacks  |
| daniels_vs_mariota.csv | Side-by-side comparison dataset      |
| vs_league_average.csv  | Performance vs league averages       |
| top_10_qbs.csv         | Top 10 quarterbacks by passing yards |

---

## Example Insights

Key findings from the analysis include:

* Jayden Daniels produced moderate passing yard totals with strong interception control
* Marcus Mariota recorded lower total passing production but similar completion efficiency
* Both quarterbacks ranked below league leaders in passing yardage
* Efficiency metrics help explain differences beyond raw totals

---

## How to Run the Project

## Step 1: Install dependencies

```
pip install pandas
```

## Step 2: Add dataset

Place the dataset in the project directory:

```
qb_2025.csv
```

## Step 3: Run analysis script

```
python qb_analysis.py
```

Output CSV files will be generated automatically.

---

## Skills Demonstrated
Showcases:

* Data cleaning with Pandas
* Feature engineering
* Statistical ranking methods
* Comparative performance analysis
* Sports analytics workflow design
* Data preparation for BI dashboards

