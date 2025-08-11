# Netflix Catalog Analysis

## 📌 Project Overview
This project analyzes the Netflix catalog to uncover insights about content distribution, trends over time, popular genres, ratings, and key contributors (actors/directors).  
The goal is to explore the dataset and present findings visually, demonstrating skills in data cleaning, feature engineering, and exploratory data analysis (EDA) with Python.

---

## 📂 Dataset
- **Source:** [Netflix Titles Dataset - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Rows:** ~8,800  
- **Columns:** 12 (original) → 16 (after feature engineering)  
- **Time Coverage:**
  - Content release years: **1925 – 2021**
  - Added to Netflix: **2008 – 2021**

---

## 📊 Analysis Steps
1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Converted dates to datetime format
   - Added `year_added` and `month_added` columns
   - Parsed `duration` into `duration_value` and `duration_unit`
2. **Exploratory Data Analysis**
   - Movies vs TV Shows distribution
   - Titles added per year
   - Top countries
   - Top genres
   - Ratings distribution
   - Movies vs TV trend over time
   - Top actors & directors
   - Duration analysis (movies in minutes, TV shows in seasons)
   - Seasonality of additions by month
3. **Visualization**
   - Created plots using Matplotlib & Seaborn
   - Saved charts to `/images` folder for easy viewing

---

## 📌 Key Insights
- Movies make up the majority of the catalog, but TV shows have grown steadily in recent years.
- A sharp increase in titles added occurred after **2016**, aligning with Netflix’s global expansion and original content strategy.
- The United States, India, and the UK are the top producers of Netflix content.
- **TV-MA** is the most common rating, indicating a focus on mature audiences.
- Most movies are between 80–120 minutes, while most TV shows have 1–2 seasons.

---

## 🛠 Technologies Used
- Python: `pandas`, `matplotlib`, `seaborn`
- Jupyter Notebook

---

## 📂 Repository Structure

netflix_analysis_project/
│
├── netflix_analysis.ipynb # Jupyter Notebook with full analysis
├── netflix_titles.csv # Dataset (if allowed by license)
├── images/ # Exported visualization PNGs
└── README.md # Project README