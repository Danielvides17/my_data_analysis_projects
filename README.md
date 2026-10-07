# Spotify Market Analysis (2000-2023): The Streaming Age

## Project Overview
This project analyzes over 1 million Spotify tracks to uncover the structural changes in music consumption and production over the first two decades of the 21st century. The goal is to translate raw audio features into actionable business insights regarding audience retention, genre popularity, and modern music production strategies.

## Tech Stack
- **Database Management & Querying:** SQL (SQLite)
- **Data Manipulation:** Python (Pandas)
- **Data Visualization:** Matplotlib & Seaborn (Custom Dark Mode Aesthetics)

## Key Business Insights
- **The "Skip" Effect:** Analyzed a systematic decline in average track duration across recent years, highlighting an industry shift to optimize monetization under current streaming payment models.
- **The Loudness War:** Filtered and visualized volume (dB) trends across the loudest genres, revealing how compression is used to capture audience attention in algorithmic playlists.
- **Audio Feature Synergy:** Developed a custom heatmap displaying a strong positive correlation (0.78) between track Energy and Loudness, while proving that absolute volume does not guarantee absolute Popularity (0.10 correlation).
- **Genre Evolution by Lustrum:** Tracked the global transition of musical tastes, observing the descent of Alt-Rock and the globalization of genres like K-Pop and Sertanejo in non-native markets.

## How to Run the Project
1. Clone the repository.
2. Ensure you have the `spotify_data.csv` dataset in the root directory.
3. Run the Jupyter Notebook `spotify_analysis_en.ipynb` cell by cell.