🏏 IPL Data Analysis: Exploring Cricket Trends with Python
A comprehensive data analysis of the Indian Premier League (IPL) focusing on match outcomes, team performance, and player statistics using Python's data science stack.

Status,Language,Libraries
✨ Complete,"<img alt=""Python"" src=""https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white""/>","<img alt=""Pandas"" src=""https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white""/> <img alt=""Matplotlib"" src=""https://img.shields.io/badge/-Matplotlib-000000?style=flat-square&logo=matplotlib&logoColor=white""/> <img alt=""Seaborn"" src=""https://img.shields.io/badge/-Seaborn-3C9A9A?style=flat-square&logo=seaborn&logoColor=white""/>"

🌟 Project Overview & Key Questions
This project dives deep into historical IPL match data to extract meaningful and actionable insights. The primary goal is to tell a compelling story about how the world's biggest T20 league operates, answering questions like:

1)🏆 Team Dominance: Which teams have the highest win-loss ratio and how does it correlate with factors like playing at home or away?
2)🪙 Toss Impact: Does the decision to bat or field first significantly influence the final match outcome across different venues?
3)⭐ Player Performance: Who are the most impactful players throughout IPL history, measured by Player of the Match awards?
4)🏟️ Venue Trends: Which grounds favor the chasing team versus the team setting a target?

✨ Analysis Highlights & Deliverables
The IPL_Data_Analysis_CLEANED.ipynb notebook contains the full pipeline:

1)🧹 Robust Data Cleaning: Essential techniques were applied to handle missing values, resolve inconsistent team names, and ensure data integrity for reliable analysis.
2)📊 Exploratory Data Analysis (EDA): A detailed dive into the dataset, visualizing distributions of win margins, total runs per season, and match outcomes.
3)📈 Impactful Visualizations: A series of easy-to-understand charts and graphs that simplify complex cricketing statistics.

Top 10 Player of the Match award winners.
Venue Performance (Win Rate Batting First vs. Chasing).
Season-by-Season Win-Loss Analysis.

🛠️ Tech Stack
This project is built using the foundational tools for Python data analysis:

Language: Python
Core Libraries:

Pandas: For data manipulation and analysis.
NumPy: For efficient numerical operations.
Matplotlib & Seaborn: For static and statistical data visualization.
Environment: Jupyter Notebook

⚙️ How to Run the Project
You can easily replicate this analysis on your local machine:

1)Clone the repository:
git clone https://github.com/dhrumil231/IPL_Data_Analysis.git

2)Navigate to the directory:
cd IPL_Data_Analysis

3)Install dependencies (requires Python/pip): 
pip install pandas numpy matplotlib seaborn jupyter

4)Launch Jupyter Notebook:
jupyter notebook

5)Open the notebook: Open the file IPL_Data_Analysis_CLEANED.ipynb to view the full analysis, code, and insights.

📂 Repository Structure
├── IPL_Data_Analysis_CLEANED.ipynb  # The core analysis notebook
└── README.md                        # This project description file

📝 Dataset
The analysis utilizes a structured dataset containing historical IPL match data with metrics on:

Match Details (Venue, Teams Played, Date)
Toss Details (Winner, Decision)
Match Outcomes (Winner, Win Margin)
Individual Awards (Player of the Match)
