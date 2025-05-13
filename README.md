# 📺 Netflix Titles Dashboard (2008 - 2021)

![Dashboard](https://raw.githubusercontent.com/iamsharononi/Netflix-Dashboard/refs/heads/main/Netflix%20Titles%20Dashboard.jpeg)<!-- Replace with your actual image URL -->

---

## 🔗 View on:
- [🔗 Connect on LinkedIn](https://www.linkedin.com/in/iamsharononi/)
- [📊 Explore Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🧠 Overview
This Power BI dashboard explores the **Netflix Titles Dataset** as of 2024.  
It reveals trends in content format, genre spread, regional distribution, and release activity through interactive visuals and filters.

---

## 📌 Table of Contents
1. [Introduction](#1-introduction)  
2. [Story of Data](#2-story-of-data)  
3. [Data Preparation](#3-data-preparation)  
4. [Initial Observations](#4-initial-observations)  
5. [Key Insights](#5-key-insights)  
6. [Dashboard Visuals](#6-dashboard-visuals)

---

## 1. Introduction
This project analyzes Netflix’s content library to uncover trends in what’s being released, who’s creating it, and how global the platform’s catalog has become. The goal is to visualize patterns that inform content strategy and platform growth.

---

## 2. Story of Data
The dataset includes metadata for Netflix Movies and TV Shows:
- `title`, `director`, `cast`, `country`, `release_year`, `date_added`, `duration`, `rating`, `genre`

---

## 3. Data Preparation
Data was cleaned and transformed using Power BI’s Power Query Editor:
- Removed nulls and standardized missing values  
- Split comma-separated fields (`cast`, `genre`, `country`)  
- Extracted `Year Added`, `Month Added`, and numeric `Duration`  
- Filtered out duplicates and normalized text fields  
- Created helper columns to distinguish **Movies** vs **TV Shows**

---

## 4. Initial Observations
- Spike in content additions between **2018–2020**
- **Movies** far outnumber **TV Shows**
- US and India dominate production origin
- Gaps in `cast` and `director` data for many international titles

---

## 5. Key Insights
- 📌 **Top Countries**: US, India, UK lead in number of titles
- 🎬 **Format Split**: Over 65% of Netflix’s library are movies
- 🕐 **Rating Trends**: Majority of titles rated **TV-MA** and **TV-14**
- 🧑‍🎓 **Popular Genres**: Documentaries, Dramas, and Comedies lead
- 🎥 **Top Directors**: Ranked by frequency of appearances across titles

---

## 6. Dashboard Visuals

This dashboard includes:

- 🎯 KPI Cards: Total Titles, Movies vs Shows, Oldest/Newest  
- 🌍 Country Heatmaps / Bar Charts  
- 🧭 Genre & Rating Distribution (TreeMap & Bar)  
- 📈 Titles Added Over Time (Line Chart)  
- ⌛ Movie Duration Ranges  
- 🎛️ Interactive Slicers: Filter by Genre, Year, Country, Type, Rating

---

## 📷 Preview

![Dashboard](https://raw.githubusercontent.com/iamsharononi/Netflix-Dashboard/refs/heads/main/Netflix%20Titles%20Dashboard.jpeg) <!-- Replace with actual image -->

---

## 🚀 Tools Used
- Power BI (Data Transformation, Dashboarding)  
- Power Query (ETL)  
- DAX (Calculated Columns & KPIs)

---

## 📬 Connect With Me
Let’s chat about data, dashboards, or design:
- 💼 [LinkedIn – @iamsharononi](https://www.linkedin.com/in/iamsharononi/)
