🎮 Steam Games Data Analysis Project
📌 Overview

This project focuses on analyzing a dataset of Steam games to uncover insights about game performance, pricing, popularity, and developer activity.
Using Python and data analysis libraries, we explore patterns and relationships within the dataset 📊.

📂 Dataset
The dataset used in this project is:
steam_games_dataset.csv

It contains information about Steam games, including:

Game name 🎮

Price 💰

Positive & negative reviews 👍👎

Number of owners 👥

Current players (CCU) 🔥

Developer & publisher 🏢

🛠️ Technologies Used

The project uses the following tools and libraries:

Python 🐍

Pandas (data manipulation)

NumPy (numerical operations)

Matplotlib (visualization)

Seaborn (advanced visualization)

🔍 Project Workflow
1. Data Loading

The dataset is loaded using Pandas.

Initial inspection is done using:

head()

info()

describe()

2. Data Cleaning 🧹

Dropped unnecessary columns (e.g., score_rank)

Handled missing values:

Replaced missing developers and publishers with "Unknown"

Checked for null values

3. Data Exploration 📊

Checked dataset shape and columns

Counted:

Free games vs Paid games

Sorted games by positive reviews

4. Data Visualization 📈

Several visualizations were created to better understand the data:

🔝 Top 5 Games by Positive Reviews

💰 Game Pricing Distribution

🔗 Price vs Positive Reviews (Scatter Plot)

🔥 Correlation Heatmap

5. Feature Engineering ⚙️

New features were created for deeper analysis:

owners_numeric → Converted ownership range to numeric

total_reviews → Positive + Negative reviews

positive_ratio → Percentage of positive reviews

6. Advanced Analysis 🚀
🥇 Top 3 Games Analysis

By number of owners

By current players (CCU)

By positive review ratio

🏢 Developers & Publishers

Top 5 developers by number of games

Top 5 publishers by number of games

🎯 Company-Specific Analysis

Analysis of major companies like Valve & Ubisoft

Compared performance based on:

CCU

Ownership

Positive ratio

📊 Key Insights

Free vs paid games distribution gives insight into market trends 💡

Popular games tend to have high engagement (CCU + reviews) 🔥

Some developers dominate the platform with a large number of games 🏢

Price does not always strongly correlate with positive reviews 🤔

▶️ How to Run the Project

Install required libraries:

pip install pandas numpy matplotlib seaborn

Open the Jupyter Notebook:

jupyter notebook steam_games_dataset.ipynb

Run all cells step by step ▶️

📁 Project Structure
├── steam_games_dataset.csv
├── steam_games_dataset.ipynb
└── README.md
💡 Future Improvements

Add machine learning models 🤖

Build a dashboard (Power BI / Tableau)

👨‍💻 Author
Youssef Abdelkader
joyousef2002@gmail.com

Created as a data analysis project to explore Steam gaming trends 🎮✨
