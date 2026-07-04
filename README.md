> **Note:** This project has evolved into [nba-lineup-analytics](https://github.com/jkalter86/nba-lineup-analytics) — an expanded platform with real multi-source data pipelines, lineup efficiency modeling, and an interactive dashboard.

# NBA Shot Chart Analysis & Optimization

## Overview
Advanced shot chart analysis system for NBA teams using spatial statistics, machine learning, and interactive visualizations. Analyzes offensive/defensive efficiency across 14 court zones to identify strategic advantages and optimize three-point line positioning.

## Key Findings
- Identified optimal 3-point line distances varying by team strategy (analysis in progress)
- Built player classification system using K-Means clustering to identify shooting archetypes
- Developed percentile-based ranking system showing each teams shooting efficiency within 14 court zones       
- Created defensive analytics revealing zone-specific weaknesses vs. specific opponents

## Tech Stack
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-red)

**Core Technologies:**
- Data Processing: Python, Pandas, NumPy
- Visualization: Plotly, Matplotlib, Seaborn
- Machine Learning: Scikit-learn (K-Means clustering)
- Data Source: NBA Stats API (nba_api)

## Features

### 1. Detailed Shot Chart DataFrames
- **12-zone court breakdown** with percentile rankings vs. league average
- **Player-level analysis** with volume filtering (minimum attempts threshold)
- **Color-coded performance indicators** using "coolwarm" colormap
- **Top 10 league-wide performers** highlighted in each zone

### 2. Interactive Offensive/Defensive Shot Charts
- Regular season and playoff analysis
- Team vs. league and team vs. team comparisons
- Distance markers for optimal shooting locations
- Player-specific drill-down capabilities

### 3. Player Classification (K-Means Clustering)
- Unsupervised learning to identify player archetypes based on shot distribution
- Helps identify player types (stretch big, corner specialist, etc.)

## Sample Outputs

• Below is the LA Clippers Chart for the 2019-20 season pre Covid-19 shutdown:


![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/LA%20Clippers.png)

-  Below are some select shotcharts for the Lakers for the complete 2019-20 season:
    - Offensive Shotchart VS League
    - Offensive Player Breakdown
    - Offensive Shotchart VS LA Clippers
    - Offensive Player Breakdown VS LA Clippers
    - Defensive Shotchart VS League
    - Defensive Shotchart VS LA Clippers

![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/Los%20Angeles%20Lakers%20Offensive%20Shotchart%20VS%20League.png)
![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/Los%20Angeles%20Lakers%20Offensive%20Player%20Breakdown%202019-20.png)
![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/Los%20Angeles%20Lakers%20Offensive%20Shotchart%20VS%20LA%20Clippers.png)
![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/Los%20Angeles%20Lakers%20Offensive%20Player%20Breakdown%20VS%20LA%20Clippers.png)
![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/Los%20Angeles%20Lakers%20Defensive%20Shotchart%20VS%20League.png)
![Alt text](https://github.com/jkalter86/NBA-Shot-Chart-Analysis/blob/master/Los%20Angeles%20Lakers%20Defensive%20Shotchart%20VS%20LA%20Clippers.png)


[Include your Lakers visualizations here]

## Data Sources
- NBA Stats API via [nba_api](https://github.com/swar/nba_api)
- 2019-20 season data (expandable to any season)

## Installation & Usage
```bash
# Clone repository
git clone https://github.com/jkalter86/NBA-Shot-Chart-Analysis.git
cd NBA-Shot-Chart-Analysis

# Install dependencies
pip install -r requirements.txt

# Run analysis
jupyter notebook "NBA Shot Charts Regular Season and Playoffs - Offensive & Defensive.ipynb"
```

## Future Work
- Complete optimal 3-point line positioning recommendations for all 30 teams
- Add expected points (xPTS) models incorporating shot quality
- Integrate player tracking data (defender distance, shot clock)
- Deploy interactive dashboard for real-time team analysis

## Project Structure
```
├── Detailed_NBA_ShotChart_DataFrame.ipynb    # Player/team statistical breakdowns
├── NBA Shot Charts Regular Season and Playoffs.ipynb  # Interactive visualizations
├── K Means Clustering for Player Type Identification.ipynb  # ML classification
└── [Visualization outputs]
```

## Author
Data Scientist specializing in sports analytics and machine learning
```
