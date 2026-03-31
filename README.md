# 🎬 Netflix Data Analysis

## 🔍 Project Overview

This project explores the Netflix dataset to uncover trends in content distribution, genre popularity, and platform growth over time. The analysis focuses on understanding how Netflix’s content library has evolved and what types of content dominate the platform.

---

## 🎯 Objectives

* Analyze the distribution of Movies vs TV Shows
* Examine how content additions have changed over time
* Identify the most popular genres on Netflix
* Clean and preprocess real-world data for analysis

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 🧹 Data Cleaning Steps

* Removed rows with missing essential values (`type`, `title`)
* Filled missing values in:

  * `country` → "Unknown"
  * `rating` → "Not Rated"
* Converted `date_added` to datetime format
* Created new features:

  * `year_added` (for trend analysis)

---

## 📊 Exploratory Data Analysis

### 📌 1. Content Type Distribution

* Compared number of Movies vs TV Shows
* Found that Movies dominate the platform

### 📌 2. Content Growth Over Time

* Analyzed number of titles added each year
* Observed rapid growth in recent years, especially after 2015

### 📌 3. Genre Analysis

* Extracted and analyzed genres from `listed_in` column
* Identified top 10 most frequent genres
* Drama, International content, and Comedies are among the most popular

---

## 📈 Key Insights

* Netflix has significantly increased content production over time
* Movies are more prevalent than TV Shows
* A few genres dominate the platform, indicating focused content strategy
* Data shows a strong trend toward global and diverse content

---

## 🚀 How to Run

1. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```

2. Run the script:

   ```bash
   python analysis.py
   ```

---

## 📌 Conclusion

This analysis highlights how Netflix’s content strategy has evolved, focusing on increasing content volume and diversifying genres. The insights can help understand audience preferences and platform growth trends.

---
