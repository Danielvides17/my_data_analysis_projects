# EdTech Analytics: Predicting Student Success & Retention (OULAD)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

## Executive Summary
In the modern EdTech landscape, student retention is as critical as acquisition. This project analyzes the **Open University Learning Analytics Dataset (OULAD)**—comprising demographic data, assessment scores, and millions of daily platform interactions (VLE clicks)—to identify behavioral patterns that predict whether a student will pass, fail, or withdraw. 

The ultimate goal of this analysis is to transition from descriptive statistics to **actionable business recommendations** that improve course completion rates.

---

## Tableau Dashboard
Interactive executive dashboard built with a custom dark/neon aesthetic to track KPIs and demographic trends.

**[LINK TO TABLEAU PUBLIC DASHBOARD]** *https://public.tableau.com/app/profile/daniel.vides/viz/OUOLAD_analysis/Dashboard1?publish=yes*

---

## Tech Stack & Methodology
* **Data Extraction & Manipulation:** SQLite, complex multi-table `JOIN` operations, Pandas.
* **Data Visualization:** Seaborn & Matplotlib (Cyberpunk color palette), Tableau.
* **Scale:** Processed multi-million row datasets (VLE interactions) by aggregating daily clicks efficiently to prevent memory bottlenecks.

---

## Key Business Insights

### 1. The "Day 0" Dropout Crisis
* **Insight:** The highest volume of student withdrawals occurs *before* the course even officially begins (Day 0) and during the first two weeks.
* **Actionable Recommendation:** The business must aggressively revamp the onboarding experience. Implementing welcome campaigns, early mentorship, and gamified introductory modules during the "negative days" will drastically reduce early churn.

### 2. Platform Engagement Predicts Success
* **Insight:** Time-series analysis of Virtual Learning Environment (VLE) clicks reveals a massive gap in engagement. Students who eventually achieve a *Pass* or *Distinction* maintain a consistently high daily click rate compared to those who *Fail* or *Withdraw*.
* **Actionable Recommendation:** Implement an automated early-warning system. If a student's daily interaction drops below the established average baseline for 3 consecutive days, trigger automated check-in emails or academic advisor interventions.

### 3. Assessment Submission Behavior
* **Insight:** A scatter plot analysis of submission dates vs. scores shows that the vast majority of students submit their work precisely on the deadline. While late submissions exist, they correlate strongly with lower final scores.

---

## Project Structure
* `university_analysis.ipynb`: The main Jupyter Notebook containing the end-to-end data pipeline, SQL queries, Pandas data wrangling, and Seaborn statistical plots.
* `Data/`: Folder containing the relational CSV files (OULAD).
* `Images/`: Stored screenshots of the Tableau dashboard and Python visualizations.

---

## How to Run the Project
1. Clone the repository: `git clone `
2. Download the dataset in this link: https://www.kaggle.com/datasets/thedevastator/open-university-learning-analytics-dataset  
3. Ensure you have the necessary libraries installed: `pip install pandas matplotlib seaborn sqlite3`
4. Open `university_analysis.ipynb` in Jupyter Lab/Notebook to view the code and visual outputs.

> *Created by Daniel Vides / https://www.linkedin.com/in/daniel-vides-517b74216/ - Data Analyst*
