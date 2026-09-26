# 🏏 IPL 2022 Data Analysis — Capstone Project

Exploratory data analysis of the IPL 2022 season: 74 matches, 20 variables, covering team performance, toss trends, win margins, player awards, and venue distribution.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-150458)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Project Overview
The Indian Premier League (IPL) is a professional T20 cricket league in India featuring city-based franchises. This project analyzes match-level data from the **2022 season** to answer a simple question: *what actually decides an IPL match — form, toss, or venue?*

The analysis is intentionally scoped to a single season (74 matches) as a focused EDA exercise, not a multi-season predictive model.

## 🔑 Key Findings
- **Gujarat Titans** won the most matches in the season — **12 wins**.
- **Winning the toss barely matters**: teams that won the toss also won the match only **48.6%** of the time — essentially a coin flip, slightly *worse* than 50/50.
- **Fielding first was the dominant strategy**: captains chose to field after winning the toss in **59 of 74 matches (~80%)**.
- **Matches were split evenly between chases and defenses**: exactly **50% won by runs, 50% won by wickets** — no strong bias toward batting or chasing sides.
- **Kuldeep Yadav** was the standout performer, winning **Player of the Match 4 times** — one more than any other player.
- **Quinton de Kock** posted the highest individual score of the season: **140 runs**.
- **Jasprit Bumrah** recorded the best bowling figures: **5 wickets for 10 runs**.
- **Wankhede Stadium** hosted the most matches (**21**), nearly a third of the entire season.

## 📊 Dataset
| Column | Description |
|---|---|
| date, venue | Match date and stadium |
| team1, team2 | Competing teams |
| toss_winner, toss_decision | Toss result and decision (bat/field) |
| first_ings_score/wkts, second_ings_score/wkts | Innings scores |
| match_winner, won_by, margin | Match result and margin |
| player_of_the_match, top_scorer, highscore | Player performance |
| best_bowling, best_bowling_figure | Bowling performance |

74 rows × 20 columns.

## 🛠️ Tools Used
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## 📈 Analysis Covered
1. Dataset overview & structure
2. Most match wins by team
3. Toss decision trends (bat vs field)
4. Toss winner vs match winner correlation
5. Win margins — runs vs wickets
6. Player of the Match leaders
7. Highest individual scores
8. Best bowling figures
9. Match distribution across stadiums

## 🚀 How to Run
```bash
git clone https://github.com/Ritik-Singh7/IPL-Analysis.git
cd ipl-2022-analysis
pip install -r requirements.txt
jupyter notebook ipl_2022_analysis.ipynb
```

## 📂 Repo Structure
```
├── ipl_2022_analysis.ipynb   # Main analysis notebook
├── IPL.csv                   # Dataset
├── requirements.txt          # Dependencies
├── ipl_2022_analysis.html    # Rendered notebook (view without running code)
└── README.md
```

## ✍️ Author
*Ritik Singh* — [LinkedIn](https://www.linkedin.com/in/ritik-singh-a8ba0233a/) · [GitHub](https://github.com/Ritik-Singh7)
