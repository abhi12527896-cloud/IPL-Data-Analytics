# 🏏 IPL Data Analysis — Exploratory Insights & Visualizations

![Animated Title](assets/animated-title.gif)

> **Project Author:** **Abhishek Kumar**  
> **Project Guide:** Mohit Sir | CETPA Infotech  
> **Tech Stack:** Python • Pandas • NumPy • Matplotlib • Seaborn • Jupyter Notebook

---

## 📌 Project Overview

This project performs an exploratory data analysis of the **Indian Premier League (IPL)** using match-level and ball-by-ball data. The presentation covers team dominance, batting milestones, bowling workload, Player of the Match impact, toss outcomes, venue usage, season trends, and strategic takeaways.

The analysis presented in the project spans **2008–2024** and focuses on turning raw cricket data into clear statistical insights and visualizations.

---

## ✨ Highlights

| Area | Key Finding |
|---|---|
| 🏆 Franchise Performance | Mumbai Indians lead with **144 wins**, followed by Chennai Super Kings with **138** |
| 🏏 Run Scoring | Virat Kohli leads the analyzed IPL run-scorer table with **8,014 runs** |
| 🎖️ Match Impact | AB de Villiers has the most Player of the Match awards: **25** |
| 🎯 Bowling | Ravichandran Ashwin leads the workload view with **4,661 deliveries** |
| 🪙 Toss | Toss winners won the match in **50.59%** of analyzed matches |
| 🏟️ Venue | Eden Gardens hosted the most matches in the presentation: **77** |
| 📈 Season Trend | Matches per season increased from **59 in 2008** to **74 in 2022/2024** |

---

## 📊 Interactive-Style Visual Summary

![Animated Franchise Bars](assets/animated-bars.gif)

The animated bars above recreate the franchise-win comparison presented in the project and make the README feel more dynamic when viewed on GitHub or another Markdown renderer that supports GIFs.

---

## 🖼️ Presentation Visuals

### Dataset Overview
![Dataset Overview](assets/dataset-overview.png)

### Most Successful IPL Franchises
![Franchise Wins](assets/franchise-wins.png)

### All-Time Leading Run Scorers
![Run Scorers](assets/run-scorers.png)

### Match-Winning Impact Leaders
![Match Winners](assets/match-winners.png)

### Bowling & Delivery Leaders
![Bowling Leaders](assets/bowling-leaders.png)

### Toss Winner vs Match Winner
![Toss Analysis](assets/toss-analysis.png)

### Top IPL Venues
![Venue Analysis](assets/venue-analysis.png)

### IPL Expansion & Matches per Season
![Season Trends](assets/season-trends.png)

---

## 🔍 Analysis Areas

### 1. Dataset Overview & Processing
- Match-level IPL data
- Ball-by-ball delivery data
- Data cleaning and validation
- Match, player, team, venue and outcome fields

### 2. Team Performance
The project compares IPL franchises using historical match wins and identifies the strongest teams across the analyzed period.

### 3. Player Performance
The analysis highlights:
- Leading run scorers
- Bowling workload
- Wicket-taking performance
- Player of the Match awards

### 4. Toss Impact
The project compares the toss winner with the eventual match winner. The presentation reports a **50.59%** toss-winner match-win rate, indicating only a marginal association.

### 5. Venue Analysis
The project identifies the venues with the highest number of hosted matches, with **Eden Gardens** at the top of the presentation's venue table.

### 6. Season Trends
Season-level match counts are visualized to show how the league's schedule expanded and changed over time.

---

## 💡 Key Strategic Takeaways

- **Franchise Consistency:** Mumbai Indians and Chennai Super Kings demonstrate sustained historical success.
- **Anchor Batting Value:** Top run scorers such as Virat Kohli and Shikhar Dhawan contribute substantial long-term batting value.
- **Toss Neutrality:** Winning the toss alone does not guarantee winning the match; execution and match conditions remain important.
- **Individual Impact:** Player of the Match awards provide another way to identify high-impact performers.

---

## 🛠️ Technology Stack

```text
Python
├── NumPy
├── Pandas
├── Matplotlib
└── Seaborn

Jupyter Notebook
```

---

## 📁 Suggested Project Structure

```text
IPL-Data-Analysis/
│
├── data/
│   ├── matches.csv
│   └── deliveries.csv
│
├── notebooks/
│   └── IPL_Cricket_Data_Analysis.ipynb
│
├── assets/
│   ├── animated-title.gif
│   ├── animated-bars.gif
│   ├── cover.png
│   ├── dataset-overview.png
│   ├── franchise-wins.png
│   ├── run-scorers.png
│   ├── match-winners.png
│   ├── bowling-leaders.png
│   ├── toss-analysis.png
│   ├── venue-analysis.png
│   ├── season-trends.png
│   └── key-takeaways.png
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### 1. Clone the project

```bash
git clone <your-repository-url>
cd IPL-Data-Analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

Open the IPL analysis notebook and run the cells sequentially.

---

## 📦 Requirements

```txt
numpy
pandas
matplotlib
seaborn
jupyter
```

---

## 📈 Example Analytical Workflow

```text
Raw IPL Data
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Statistical Analysis
     ↓
Visualization
     ↓
Pattern Identification
     ↓
Strategic Insights
```

---

## 📋 Data Quality Notes

The project presentation combines **match-level** and **ball-by-ball** IPL analysis. Reported figures should therefore be interpreted according to the specific dataset/table used for each analysis rather than assuming every metric comes from the same row-level source.

---

## 🎓 Learning Outcomes

This project demonstrates practical skills in:

- Data loading and cleaning
- Pandas data manipulation
- NumPy-based analysis
- Grouping and aggregation
- Statistical summaries
- Data visualization
- Cricket-domain exploratory analysis
- Insight generation
- Jupyter Notebook workflow

---

## 👨‍💻 Project Author

**Abhishek Kumar**

**Project Guide:** Mohit Sir — CETPA Infotech

---

## ⭐ Final Note

This README is designed to work as a **dynamic GitHub project landing page** with animated title and bar graphics, presentation screenshots, structured sections, and reproducible setup instructions.

If you fork or reuse the project, replace the placeholder repository URL and add the original dataset/source information used by your notebook.

