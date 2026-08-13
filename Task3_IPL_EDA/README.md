# IPL Exploratory Data Analysis

## 1. Project Overview

This project performs Exploratory Data Analysis (EDA) on IPL cricket data.

The analysis focuses on identifying:

- Most winning teams
- Top run scorers
- Stadium/venue trends

Additional analysis was also performed on toss winners and toss decisions.

## 2. Objective

The main objective of this project is to analyze IPL match and ball-by-ball data and extract useful insights using Python data analysis and visualization techniques.

## 3. Dataset

The project uses two datasets:

- `matches.csv` - Match-level IPL information
- `deliveries.csv` - Ball-by-ball IPL information

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 5. Data Analysis

### Most Winning Teams

The number of matches won by each team was calculated using the `winner` column from the match dataset.

The top 10 teams were visualized using a bar chart.

### Top Run Scorers

The `batsman` and `batsman_runs` columns from the deliveries dataset were used to calculate the total runs scored by each batsman.

The top 10 run scorers were visualized using a bar chart.

### Stadium Trends

The `venue` column was analyzed to identify the stadiums that hosted the highest number of IPL matches.

The top 10 venues were visualized using a bar chart.

### Toss Analysis

Additional analysis was performed to determine:

- Teams with the most toss wins
- Most common toss decisions
- Percentage of matches where the toss winner also won the match

## 6. Key Results

The exact results are available in:

`results/ipl_eda_summary.csv`

The summary contains:

- Most winning team
- Number of wins
- Top scorer
- Top scorer's total runs
- Most-used venue
- Number of matches at the most-used venue
- Percentage of matches where toss winner also won the match

## 7. Visualizations

The project contains visualizations for:

- Top 10 winning teams
- Top 10 run scorers
- Top 10 venues
- Top 10 toss winners
- Toss decisions
- Toss decision distribution

All visualizations are stored in the `images` folder.

## 8. Project Structure

Task3_IPL_EDA/

├── dataset/

│   ├── matches.csv

│   └── deliveries.csv

├── notebooks/

│   └── IPL_EDA.ipynb

├── images/

│   ├── top_10_winning_teams.png

│   ├── top_10_run_scorers.png

│   ├── top_10_venues.png

│   ├── top_10_toss_winners.png

│   ├── toss_decisions.png

│   └── toss_decision_distribution.png

├── results/

│   ├── team_wins.csv

│   ├── top_10_scorers.csv

│   ├── venue_trends.csv

│   ├── toss_winners.csv

│   ├── toss_decisions.csv

│   ├── matches_analyzed.csv

│   └── ipl_eda_summary.csv

└── README.md

## 9. Conclusion

The IPL dataset was explored using Python to identify important patterns in team performance, individual batting performance, venue usage, and toss decisions.

The analysis demonstrates how Exploratory Data Analysis can be used to transform raw IPL match data into meaningful insights and visualizations.