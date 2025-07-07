# 📺 Netflix Dashboard – Tableau Visualization

> **By Jeffrey John Kennedy**

This project presents a comprehensive Tableau dashboard built using Netflix’s global catalog data. It allows users to explore content distribution by country, ratings, genres, and release trends through interactive visualizations.
<img width="1430" alt="image" src="https://github.com/user-attachments/assets/53050082-ee7e-4eab-a348-d84144e60520" />

---

## 📊 Dashboard Features

### ✅ Interactive Filters
- **Type**: Filter between *Movies* and *TV Shows*
- **Title**: Drill down into specific Netflix titles

### 🌍 Global Insights
- **Map Visualization**: Total number of Movies & TV Shows by country
- **Ratings Breakdown**: Count of titles by rating (e.g., TV-MA, PG, R)

### 📈 Temporal Trends
- **Releases Over Time**: Year-wise distribution of content from 2008 to 2020

### 🍿 Genre Analytics
- **Top 10 Genres**: Horizontal bar chart of the most frequent genres
- **Genre Combinations**: Mixed-genre insights like *Documentaries + International Movies*

### 📦 Content Proportion
- **Movies vs TV Shows**: Donut chart showing their relative proportions

### 🧾 Title Metadata (Dynamic)
For any selected title, the dashboard dynamically displays:
- Rating, Release Year, Duration, Genre(s)
- Description from dataset
- Date Added to Netflix

---

## 📁 Dataset

**File**: `netflix_titles.csv`  
**Source**: Netflix’s global catalog metadata  
**Total Records**: ~6,200  
**Main Columns**:
- `show_id`, `type`, `title`, `director`, `cast`, `country`
- `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

> Includes Netflix content across multiple countries for both Movies and TV Shows.

---

## 🛠️ Tools Used

- **Tableau Public** – For interactive dashboard creation
- **Tableau Prep / In-Built Cleaning** – To handle nulls, filters, and aggregations
- **CSV Dataset** – Cleaned and imported directly into Tableau

---

## 🌐 Live Dashboard

🔗 [View on Tableau Public](https://public.tableau.com/app/profile/jeffrey.john.kennedy/viz/NetflixDashboard_17518571428460/Netflix)

---

## 🧠 Key Insights

- **TV-MA** and **TV-14** are the most common ratings.
- **United States** has the highest volume of Netflix content.
- **Documentaries** and **Stand-Up Comedy** top the genre charts.
- Sharp rise in Netflix content between **2016–2019**, followed by a drop in 2020 (possibly due to COVID-19 impacts).

---



