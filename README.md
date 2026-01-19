# Netflix_Capstone_project

🎬 Netflix Capstone Project – Exploratory Data Analysis (EDA)
📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the Netflix Titles dataset (2021) to uncover insights about content trends, genres, countries, ratings, release patterns, and content evolution over time.
The analysis uses Python data analysis and visualization libraries to transform raw data into meaningful business insights.

🎯 Objectives

Understand Netflix’s content distribution (Movies vs TV Shows)

Identify top genres and countries

Analyze content release trends over time

Study ratings distribution

Explore movie duration patterns

Perform time-series analysis on content additions

Visualize genre trends and content evolution

📂 Dataset Information

Source: Netflix Titles Dataset (2021)

Total Records: 8,807

Columns: 12

show_id, type, title, director, cast, country,
date_added, release_year, rating, duration, listed_in, description

🛠️ Technologies & Libraries Used

Python

Pandas – Data cleaning & manipulation

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualizations

Plotly Express – Interactive charts

🧹 Data Cleaning Steps

Removed duplicate records

Handled missing values:

Filled country and director with "Unknown"

Removed rows with missing date_added and rating

Converted date fields for time-series analysis

Extracted numeric values from duration fields

📊 Key Analysis & Visualizations
1️⃣ Descriptive Statistics

Release years range from 1925 to 2021

Majority of content released after 2010

2️⃣ Genre Analysis

Identified Top 10 most common genres

Visualized genre distribution using bar charts

Explored genre trends over time

3️⃣ Content Type Distribution

Compared Movies vs TV Shows

Movies dominate the Netflix catalog

4️⃣ Country-wise Analysis

Identified Top 15 content-producing countries

USA leads, followed by India and the UK

5️⃣ Time Series Analysis

Analyzed content additions per year

Observed rapid growth after 2015

6️⃣ Rating Analysis

Visualized Top 10 Netflix ratings

Analyzed average movie duration by rating

7️⃣ Movie Duration Analysis

Most movies fall between 80–120 minutes

Studied average duration trends over release years

📈 Key Insights

Netflix heavily expanded its content library after 2015

Drama and International content dominate the platform

Movies are more prevalent than TV Shows

The USA contributes the most content

Movie durations have remained relatively stable over time

🚫 Limitations

No user reviews or sentiment data available

Language-specific analysis not possible

IMDb ratings are manually assigned (not from dataset)

🚀 Future Improvements

Add sentiment analysis using external review data

Integrate IMDb ratings API

Build an interactive dashboard

Apply machine learning for content recommendation

📁 Project Structure
📦 Netflix-Capstone-Project
 ┣ 📜 netflix.ipynb
 ┣ 📜 netflix_titles_2021.csv
 ┗ 📜 README.md

🙌 Conclusion

This project demonstrates strong skills in data cleaning, visualization, and exploratory analysis. It provides actionable insights into Netflix’s content strategy and serves as a solid portfolio project for Data Analyst roles.
