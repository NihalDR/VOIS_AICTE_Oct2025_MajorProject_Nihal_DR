# VOIS_AICTE_Oct2025_MajorProject_Nihal_DR
# 📊 Netflix Content Trends Analysis
## About the Author

- **Name:** Nihal DR
- **College:** CMR Institute of Technology
- **Branch:** Artificial Intelligence & Data Science (AI&DS)

## 📌 Problem Statement
Netflix has become one of the most prominent global streaming platforms, continuously expanding its library with original productions and licensed content. However, with growing competition from Amazon Prime, Disney+, and regional OTT providers, Netflix must strategically analyze its content catalog to identify strengths, gaps, and opportunities.  

This project addresses **Content Trends Analysis for Strategic Recommendations**, aiming to uncover how Netflix’s content distribution (Movies vs. TV Shows, genres, and country contributions) has evolved over the years.

---

## 🎯 Objectives
1. Analyze the distribution of **Movies vs. TV Shows** over the years.  
2. Identify the most common **genres** and how their popularity has changed.  
3. Compare **country-wise contributions** to Netflix’s catalog.  

---

## ✅ Expected Outcomes
- A clear understanding of how Netflix’s **content strategy has evolved**.  
- Identification of **top-performing genres** and categories.  
- Strategic recommendations on **which content types and regions Netflix should focus on** in the future.  

---

## 📂 Dataset
The dataset used is **Netflix Dataset.csv** (7,789 rows, 11 columns).  
Columns include:  

- `Show_Id`: Unique identifier  
- `Category`: Movie or TV Show  
- `Title`: Name of the content  
- `Director`: Director(s) of the content  
- `Cast`: Main cast members  
- `Country`: Country of origin  
- `Release_Date`: Release date (month, day, year)  
- `Rating`: Audience rating (e.g., PG-13, TV-MA)  
- `Duration`: Minutes (for movies) or Seasons (for TV shows)  
- `Type`: Genre/sub-categories  
- `Description`: Short description  

---

## 🛠️ Methodology
The analysis is structured in three main parts:

### 1. Movies vs. TV Shows Distribution
- Extract release **year** from `Release_Date`.  
- Compare counts of Movies vs. TV Shows over the years.  
- Visualize using **stacked bar charts** and **proportion plots**.  

### 2. Genre Trends Analysis
- Split `Type` column into individual **genres**.  
- Identify **top 15 genres**.  
- Track how their popularity changed year by year.  
- Calculate **growth rates** (early vs. recent years).  

### 3. Country-Wise Contributions
- Split `Country` column for multiple countries.  
- Identify **top contributing countries overall**.  
- Visualize trends of top countries over time.  

---

## 📊 Visualizations & Outputs
The notebook generates:
- 📈 Movies vs. TV Shows trends (counts and proportions).  
- 🎭 Top 15 genres over time.  
- 🌍 Country-wise contributions and growth.  
- 👨‍💻 Top directors by content volume.  
- 🎟️ Distribution of audience ratings.  
- 🕒 Duration analysis (minutes & seasons).  

Saved outputs include:
- `year_category_counts.csv`  
- `genre_year_counts_top15.csv`  
- `genre_growth_summary_top15.csv`  
- `top_countries_overall.csv`  
- `country_year_counts_top10.csv`  
- `top_directors.csv`  
- `rating_counts.csv`  
- `duration_stats.csv`  
- `recommendations_draft.txt`  

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone [https://github.com//netflix-trends-analysis.git](https://github.com/NihalDR/VOIS_AICTE_Oct2025_MajorProject_Nihal_DR.git)
   cd netflix-trends-analysis

