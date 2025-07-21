# 🏏 IPL Team Performance Analysis Dashboard

A Power BI project visualizing IPL team and player performances from 2008 to 2025 using advanced DAX, data modeling, and interactive visualizations.

---

## 📌 Problem Statement

Analyze IPL match, player, and ball-by-ball data to understand trends, compare team performances, and build season-wise dynamic points tables with key performance metrics.

---

## ✅ Solution

Built an end-to-end **Power BI dashboard** combining four large datasets to uncover team strategies, individual milestones, and performance insights using DAX, slicers, and interactive visuals.

---

## 🧰 Tools & Technologies

- 🧩 **Power BI** – Dashboards, visuals, interactivity  
- 📐 **DAX** – KPIs, calculated columns, dynamic tables  
- 🔗 **Data Modeling** – Relationship-building across multiple tables  
- 🧮 **Excel** – Pre-processing and transformations

---

## 📁 Dataset Summary

The project uses 4 major `.csv` files:

| File Name             | Description                             |
|-----------------------|-----------------------------------------|
| `ball_by_ball_data`   | Delivery-level data from all matches     |
| `ipl_matches_data`    | Match metadata (season, teams, result)   |
| `players-data-updated`| Player profiles with teams               |
| `teams_data`          | Team codes and franchise info            |

All files are connected via Power BI's relationship model for a unified schema.

---

## 🧮 DAX Measures & Metrics

- 🟠 **Orange Cap Tracker**
  - Top run-scorer of the season
  - Player Name, Team, Runs Scored, with image

- 🟣 **Purple Cap Tracker**
  - Top wicket-taker
  - Player Name, Team, Total Wickets, with image

- 💥 **Most Sixes/Fours**
  - Player Name, Team Name
  - Total Sixes/Fours hit, player photos included

- 📊 **Team Performance Stats**
  - Matches Played, Matches Won
  - No Results, Ties, Total Points

- 💯 **Batting Milestones**
  - Number of Centuries (100+)
  - Number of Half Centuries (50–99)

- 📈 **Dynamic Points Table**
  - Season-wise points, wins, losses
  - Built fully in DAX, controlled with slicers

---

## 📊 Dashboards

### 🧠 All-in-One: Team & Player Analysis

A single dynamic dashboard offers complete analysis:

- 📅 **Season Slicer** – Filter all visuals by season
- 🟠 **Orange Cap** – Top scorer with image & stats
- 🟣 **Purple Cap** – Top wicket-taker with visuals
- 💥 **Power Hitters** – Most sixes and fours by player/team
- 💯 **Milestones** – Count of 100s & 50s per season
- 📈 **Points Table** – Live updating by filters
- 🏏 **Match Result Analysis** – Interactive win/loss chart

> ⚙️ Slicers and filters make every metric **dynamic** and **explorable**.

---

## 🔍 Key Insights

- 🏆 Power shifts visible post-2017 with rising new contenders  
- 📉 Teams underperform significantly in away games  
- 💣 High six-hitting teams win more matches, especially post-2022  
- 📊 Tight finishes (wins by <10 runs or <2 wickets) increasing  
- 🧮 Death overs show highest economy swings across all seasons  

---

## 🚀 Future Enhancements

- ➕ Add player type segmentation (batsman, bowler, all-rounder)  
- 🧠 Introduce match prediction models  
- 🎯 Enable "What-If" team composition and toss simulations  

---

## 🙋‍♂️ Author

**Piyush Agarwal**  
📧 agpiyush84@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/agpiyush84/)

---

## 📦 File & Performance Notes

- `ball_by_ball_data.csv` (~53MB) powers all granular delivery-level metrics  
- Data model optimized for **fast report performance** even with large files  
- Final `.pbix` file included for full reproducibility

---

