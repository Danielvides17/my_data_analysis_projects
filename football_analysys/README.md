# Football (Soccer) Matches Analysis (2023-2026)

## Project Overview
This project analyzes over 100 football games to search what are the key factors that ensure teams to win. Utilizing a dataset of national and international games played between September 2023 and April 2026, the analysis explores the statistical impact of playing at home, team playstyles (possession and passing), and offensive metrics.

## Tools
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy
- **Database:** SQLite3 (utilized via an in-memory database for efficient SQL querying)

## Key Business Insights
- **The "Skip" Effect:** Analyzed a systematic decline in average track duration across recent years, highlighting an industry shift to optimize monetization under current streaming payment models.
- **The Loudness War:** Filtered and visualized volume (dB) trends across the loudest genres, revealing how compression is used to capture audience attention in algorithmic playlists.
- **Audio Feature Synergy:** Developed a custom heatmap displaying a strong positive correlation (0.78) between track Energy and Loudness, while proving that absolute volume does not guarantee absolute Popularity (0.10 correlation).
- **Genre Evolution by Lustrum:** Tracked the global transition of musical tastes, observing the descent of Alt-Rock and the globalization of genres like K-Pop and Sertanejo in non-native markets.

## Key Insights & Findings
- **The Home Advantage:**
Home teams win significantly more often (44.7%) compared to away teams (30.6%), while 24.7% of games end in a draw. Home teams also score more goals on average (1.53 vs 1.22).

- **Top Performers (Minimum 30 matches):**
Best Attackers: Bayern Munich (3.04 goals/game), PSV, and Barcelona lead in average goals scored per match.
Best Defenders: Tokushima (0.65 goals/game), Coritiba, and ZED concede the fewest goals on average.

- **Possession vs. Win Rate:**
Home teams with high possession (>60%) and more passes have a 44% win rate.
Interestingly, home teams with low possession (<41%) and fewer passes still maintain a 42% win rate, indicating that home advantage strongly mitigates the need for a possession-based playstyle.
Away teams that heavily dominate possession only win 30% of their matches, further emphasizing the difficulty of winning on the road regardless of tactical dominance.

- **Offensive Correlations:**
Total shots have a weak correlation with actual goals. However, Expected Goals (xG), Shots on Target, and Touches in the Opponent's Box show a much stronger correlation and are better predictors of a team's scoring success.

## How to Run the Project
1. Clone this repository.
2. Ensure the football_dataset.csv file is located in the same directory as the notebook https://www.kaggle.com/datasets/omarameen99/football-matches-data-from-soccerway 
3. Install the required dependencies:
pip install pandas matplotlib seaborn numpy
4. Open and run the Jupyter Notebook to view the Python code, SQL queries, and neon-styled visualizations.