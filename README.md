
# netflix-data-analysis
Netflix dataset analysis using Python &amp; Pandas

📌 Overview
This project performs Exploratory Data Analysis (EDA) on a Netflix movies dataset to uncover patterns, trends, and insights. The analysis involves:

Data cleaning and preprocessing

Descriptive statistics

Visualization of numeric and categorical features

Correlation analysis

Outlier detection

The objective is to understand the dataset’s characteristics and prepare it for further analysis or predictive modeling.
📂 Dataset
File: mymoviedb.csv

Description: Metadata about Netflix movies including popularity, ratings, genres, languages, and release dates.

Key Columns:

Title — Movie name

Release_Date — Date of release

Popularity — Popularity score

Vote_Count — Number of votes

Vote_Average — Average rating

Original_Language — Primary language

Genre — Movie genre

📊 Analysis Steps
Data Loading — Import CSV file and preview dataset.

Data Cleaning — Handle missing values, convert Release_Date to datetime.

EDA —

Distribution of numeric columns

Top languages and genres

Correlation heatmap

Outlier detection


Outlier detection

🛠 Tools & Libraries
Python 3.x

Pandas — Data manipulation

Matplotlib & Seaborn — Visualization


📈 Key Insights
Certain genres and languages dominate the Netflix movie library.

Popularity is loosely correlated with vote count but not strongly with ratings.

A small number of movies receive disproportionately high votes and popularity scores, indicating outliers.
