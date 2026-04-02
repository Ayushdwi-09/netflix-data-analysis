# 🎬 Netflix Data Dashboard

## 🔍 Project Overview
This project presents an interactive Netflix data dashboard that visualizes trends in content distribution, growth, genres, countries, and ratings. It transforms raw dataset insights into a visually engaging interface, enabling users to explore how Netflix’s content library has evolved over time.

---

## 🎯 Objectives
- Visualize the distribution of Movies vs TV Shows  
- Analyze yearly trends in content additions  
- Identify the most popular genres and countries  
- Explore content ratings distribution  
- Build an interactive dashboard for data exploration  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- HTML  
- CSS  
- JavaScript  

---

## 🧹 Data Preparation
- Removed rows with missing essential values (`type`, `title`)  
- Handled missing values:
  - `country` → "Unknown"  
  - `rating` → "Not Rated"  
- Converted `date_added` to datetime format  
- Created new feature:
  - `year_added` for trend analysis  

---

## 📊 Dashboard Highlights

### 📌 Content Type Distribution
- Donut chart representing Movies vs TV Shows  
- Movies dominate the platform  

### 📌 Content Added Over Time
- Year-wise timeline visualization  
- Significant growth observed after 2015  

### 📌 Top Genres
- Top 10 genres displayed using bar charts  
- Most common:
  - International Movies  
  - Dramas  
  - Comedies  

### 📌 Top Countries
- Highlights leading content-producing countries  
- United States, India, and United Kingdom lead  

### 📌 Content Ratings
- Distribution of ratings using grid layout  
- TV-MA and TV-14 are most frequent  

### 📌 Release Year Trends
- Shows content distribution from 2007–2021  

---

## 📈 Key Insights
- Rapid content growth after 2015  
- Movies significantly outnumber TV Shows  
- Strong focus on international and diverse content  
- A few genres dominate the platform  
- Wide global content distribution  

---

## 📌 Conclusion
This dashboard provides a comprehensive visual analysis of Netflix’s content ecosystem. It highlights platform growth, genre dominance, and global expansion, offering valuable insights into Netflix’s evolving content strategy.
