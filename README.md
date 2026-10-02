# IPL 2008–2024 — Exploratory Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Indian Premier League (IPL) match-level data from 2008 to 2024 using Python.

The analysis explores team performance, match results, toss decisions, venues, winning margins, season-wise trends, and other important patterns in IPL matches.

## 🎯 Objectives

- Analyze IPL matches from 2008 to 2024
- Study season-wise match trends
- Analyze team wins and appearances
- Examine toss decisions and their relationship with match results
- Identify popular IPL venues
- Analyze winning margins
- Study match result types
- Visualize important patterns using charts and heatmaps
- Generate useful insights from IPL match data

## 📊 Dataset

**Dataset:** IPL Match-Level Dataset  
**Period:** 2008–2024  
**Number of Matches:** 1,095  
**Number of Columns:** 20

The dataset contains information related to IPL matches, including:

- Season
- Teams
- Venue
- Toss winner
- Toss decision
- Match winner
- Result
- Winning margin
- Player of the Match
- Match outcome information

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📈 Analysis Performed

The project includes analysis of:

1. Missing values
2. Matches by season
3. Average winning margin by season
4. Matches played by team
5. Wins by team
6. Win percentage by team
7. Team-season wins heatmap
8. Toss decision distribution
9. Toss winner vs match winner
10. Toss decisions by season
11. Top IPL venues
12. Match result types
13. Defended vs chased matches
14. Head-to-head team performance
15. Super-over distribution
16. Correlation analysis

## 🔍 Key Findings

Some observations from the analysis include:

- Total matches analyzed: **1,095**
- Mumbai Indians recorded the highest number of match wins in the dataset: **144**
- Mumbai Indians also had the highest number of recorded match appearances: **261**
- Eden Gardens recorded the highest number of matches: **77**
- The most common result type was **wickets**
- The toss winner also won the match in approximately **50.83%** of matches
- There were **14 tied matches**
- There were **5 no-result matches**
- There were **14 super-over matches**
- There were **21 D/L matches**
- The largest recorded victory by runs was **146 runs**
- The largest recorded victory by wickets was **10 wickets**

## 📁 Project Structure

```text
IPL-2008-2024-EDA/
│
├── IPL_2008_2024_EDA.ipynb
├── matches.csv
├── IPL_2008_2024_EDA_Project_Report.pdf
├── README.md
│
└── charts/
    ├── 01_missing_values.png
    ├── 02_matches_by_season.png
    ├── 03_average_margin_by_season.png
    ├── 04_matches_played_by_team.png
    ├── 05_wins_by_team.png
    ├── 06_win_percentage_by_team.png
    ├── 07_team_season_wins_heatmap.png
    ├── 08_toss_decision_distribution.png
    ├── 09_toss_winner_match_winner.png
    ├── 10_toss_decisions_by_season.png
    ├── 11_top_venues.png
    ├── 12_match_result_types.png
    ├── 13_defended_vs_chased.png
    ├── 14_head_to_head_heatmap.png
    ├── 15_super_over_distribution.png
    └── 16_correlation_heatmap.png
