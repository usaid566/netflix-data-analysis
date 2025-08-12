# Netflix Data Analysis

Analyze Netflix movies data using Python and Pandas

---

## 📌 Overview

This project conducts **Exploratory Data Analysis (EDA)** on a Netflix movies dataset to discover patterns, trends, and actionable insights. The analysis covers:

- **Data Cleaning & Preprocessing**
- **Descriptive Statistics**
- **Visualization of Numeric & Categorical Features**
- **Correlation Analysis**
- **Outlier Detection**

The goal is to understand the dataset’s characteristics and prepare it for further analysis or predictive modeling.

---

## 📂 Dataset

- **File:** `mymoviedb.csv`
- **Description:** Contains metadata about Netflix movies, including popularity, ratings, genres, languages, and release dates.

### Key Columns

| Column             | Description                  |
|--------------------|-----------------------------|
| `Title`            | Movie name                  |
| `Release_Date`     | Date of release             |
| `Popularity`       | Popularity score            |
| `Vote_Count`       | Number of votes             |
| `Vote_Average`     | Average rating              |
| `Original_Language`| Primary language            |
| `Genre`            | Movie genre                 |

---

## 📊 Analysis Workflow

1. **Data Loading**
   - Import CSV file and preview dataset.
2. **Data Cleaning**
   - Handle missing values
   - Convert `Release_Date` to datetime
3. **EDA**
   - Distribution of numeric columns
   - Top languages and genres
   - Correlation heatmap
   - Outlier detection

---

## 🛠 Tools & Libraries

- **Python 3.x**
- **Pandas** — Data manipulation
- **Matplotlib & Seaborn** — Data visualization

---

## 📈 Key Insights

- Certain genres and languages dominate the Netflix movie library.
- Popularity is loosely correlated with vote count but not strongly with ratings.
- A small number of movies receive disproportionately high votes and popularity scores, indicating outliers.

---

*Feel free to explore the repository and reach out for any suggestions or queries!*
