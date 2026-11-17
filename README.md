# Synent Task 3: Netflix Exploratory Data Analysis

**Author:** Gershom  Nyamongo Mosora

**Program:** Synent Technologies - Data Science Internship (Task 3)

**Demo video:** https://youtu.be/HrEQ1YUMR74

## Problem Statement
Explore the Netflix catalogue to identify trends and patterns in what content is available, where it comes from and how it has changed over time, using summary statistics, correlation analysis and graphs.

## Dataset
Netflix Movies and TV Shows dataset (Kaggle): 8,807 titles (6,131 movies and 2,676 TV shows) and 12 columns, including type, country, date added, release year, rating, duration and genres.

## Approach
- Cleaned and prepared the data: moved three misplaced movie lengths, filled missing text values, converted dates, and built numeric features (movie minutes, seasons, number of genres, year added)
- Summary statistics
- Correlation analysis between release year, year added, number of genres and movie length
- Trend analysis: titles added per year, movie length over time, top countries and top genres

## Results
- Titles added peaked in 2019 and fell afterwards (2021 is a partial year)
- The United States leads by a wide margin, followed by India and the United Kingdom
- Movies have become shorter over time, from about 116 minutes (pre-1980) to about 95 minutes (after 2015)
- About 71% of titles were released in 2015 or later
- Movies with more genre tags tend to be longer (correlation about 0.41)

## Tools
Python, pandas, matplotlib, seaborn, Jupyter Notebook
