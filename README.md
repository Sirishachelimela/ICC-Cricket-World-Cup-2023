# 🏏 ICC Cricket World Cup 2023 – Data Analysis (Python EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **ICC Cricket World Cup 2023** dataset to uncover insights related to:
- Player performances (batting & bowling)
- Match outcomes
- Team dominance
- Player roles and trends across the tournament

The analysis is done using **Python**, focusing on clean data preparation, statistical analysis, and visual storytelling.

---

## 🎯 Project Objectives
- Identify the **Top 10 Batsmen** and **Top 10 Bowlers** of the tournament
- Analyze **strike rates**, **economy rates**, and **match-winning teams**
- Understand **player role distribution**
- Study **match trends over time**
- Convert raw cricket data into meaningful insights

---

## 📂 Datasets Used
The project uses four CSV files:
- `batting_summary.csv` – Batting performance per match
- `bowling_summary.csv` – Bowling statistics per match
- `match_schedule_results.csv` – Match results and venues
- `world_cup_players_info.csv` – Player profiles and roles

---

## 🧹 Data Cleaning & Preparation
Key cleaning steps performed:
- Checked missing values across all datasets
- Removed non-essential column (`image_of_player`)
- Filled missing values:
  - `bowlingStyle` → "Not Applicable"
  - `description` → "No description"
- Converted date columns to proper `datetime` format
- Created derived fields such as:
  - `duration_min` (from milliseconds)
  - `release_year` / match timelines

These steps ensured **data consistency and reliability** before analysis.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Batting Analysis
- Top 10 run scorers of the tournament
- Strike rate analysis based on total runs and balls faced
- Visualization using bar charts

### 🔹 Bowling Analysis
- Top 10 wicket takers
- Bowling economy rate calculation
- Comparison of bowler efficiency

### 🔹 Team Performance
- Matches won by each team
- Team dominance analysis using bar charts

### 🔹 Player Profile Analysis
- Distribution of player roles (Batsman, Bowler, All-rounder, Wicket-keeper)
- Understanding squad composition

### 🔹 Match Trends
- Matches played over time
- Tournament progression visualization

---

## 📈 Visualizations Used
- Bar charts for top performers
- Pie charts for player role distribution
- Line charts for match timelines
- Clean, readable plots using **Matplotlib & Seaborn**

---

## 🔍 Key Insights
- A small group of batsmen contributed a large portion of total runs
- Certain bowlers consistently dominated wicket tallies
- Team wins were unevenly distributed, showing dominance by top teams
- All-rounders played a crucial balancing role in team composition
- Match frequency followed a steady schedule with peak periods

---

## ✅ Conclusion
This analysis successfully highlights **performance patterns**, **key contributors**, and **team strengths** in the ICC Cricket World Cup 2023.  
It demonstrates how structured EDA can turn raw sports data into **clear, actionable insights**.

---

## 💡 Recommendations
- Teams should focus on nurturing **consistent middle-order batsmen**
- Bowlers with low economy and high wickets should be prioritized
- Data-driven selection strategies can improve team balance
- Future analysis can include:
  - Venue-wise scoring patterns
  - Player consistency across matches
  - Predictive modeling for match outcomes

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

---

## 📬 Author
**Sirisha Chelimela**  
Business Analyst | Data Analytics Enthusiast  
GitHub: https://github.com/SirishaChelimela

---

⭐ If you found this project useful, feel free to star the repository!
