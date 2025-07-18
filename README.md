#  IMDb Top 1000 Movie Analysis – EDA & Visual Insights

This project explores the top 1000 movies from IMDb using Python and visual storytelling techniques to understand trends, audience preferences, and revenue dynamics.

---

##  Objective

Perform Exploratory Data Analysis (EDA) on real-world movie data to uncover insights into what factors influence critical and commercial success in the film industry.

---

##  Dataset Overview

- **Source**: Public GitHub IMDb dataset  
- **Rows**: 1000 movies  
- **Columns**: Title, Genre, Director, Runtime, Ratings, Revenue, Votes, etc.  
- **Real-World Domain**: Entertainment / Film Analytics

---

##  Tools Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- Google Colab
- Canva (for Insight Card design)

---

##  Steps Performed

###  Phase 1: Data Cleaning & Preparation
- Loaded CSV dataset using `pandas`
- Checked for missing values → None found
- Removed duplicates (if any)
- Renamed columns for clarity
- Converted columns to correct data types (`int`, `float`, etc.)

###  Phase 2: Exploratory Data Analysis (EDA)
Created 5 visualizations to explore:
- Distribution of IMDb ratings
- Top 10 most frequent genres
- Average revenue by year
- Correlation heatmap between key features
- Revenue vs IMDb rating (scatter)

###  Phase 3: Insights & Recommendation
- Identified trends in genre popularity and rating-revenue disconnect
- Designed a **Client Insight Card** (1-page summary) with:
  - 3 core insights
  - 1 business recommendation
  - 2 visual highlights

---

##  Key Insights

1. **Drama**, **Action**, and **Comedy** dominate the top genres
2. High IMDb ratings ≠ High revenue — some average-rated films earn more
3. Strong correlation between **Votes and Rating**

---

##  Recommendation

Studios and platforms should focus on **Drama-Action hybrids** with runtimes around **120 minutes**, which show the highest balance between critical and commercial performance.

---

##  Project Files

| File | Description |
|------|-------------|
| `IMDb_EDA_Analysis.ipynb` | Full analysis notebook |
| `README.md` | This file! Describing the workflow |

---

You can view and run the full project notebook here:  
**[Open in Colab →](https://colab.research.google.com/drive/1mJjg4bCy_ImhfPuDn8LXjOrvRLuAu3c_?usp=sharing)**


> 
