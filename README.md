# Capstone Project 2: Amazon Prime TV Shows and Movies

# Project Overview
In today's competitive streaming industry, platforms like Amazon Prime Video are constantly expanding their content libraries to cater to diverse audiences. Data-driven insights play a crucial role in understanding trends, audience preferences, and content strategy. 

This project explores a comprehensive dataset of Amazon Prime's content library (available in the United States) to extract valuable business insights. By analyzing over 9,000 unique titles and 124,000+ cast credits, this project aims to uncover key trends that influence subscription growth, user engagement, and content investment strategies.

# Problem Statement
The primary objective is to analyze the Amazon Prime dataset to extract valuable insights regarding:
1. Content Diversity: What genres and categories dominate the platform?
2. Regional Availability: How does content distribution vary across different regions?
3. Trends Over Time: How has Amazon Prime’s content library evolved over the years?
4. Ratings & Popularity: What are the highest-rated or most popular shows and movies?

## 📊 Dataset Description
The dataset consists of two CSV files containing a mix of categorical and numeric values:
* `titles.csv`: Contains metadata for 9,000+ titles (movies and TV shows), including ID, title, type, description, release year, age certification, runtime, genres, production countries, seasons, and IMDb/TMDB scores.
* `credits.csv`: Contains 124,000+ credits for actors and directors associated with the titles.

## 🛠️ Tech Stack & Libraries
* **Language**: Python
* **Environment**: Google Colab / Jupyter Notebook
* **Data Manipulation**: Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn
* **Utilities**: `ast` (for parsing stringified lists)

## 🔍 Key Insights & Findings
1. **Movies vs. TV Shows**: Movies significantly outnumber TV shows on Amazon Prime, indicating a heavy reliance on feature-length content to retain subscribers.
2. **Top Genres**: **Drama** and **Comedy** are by far the most dominant genres on the platform, pointing to a mass-market, broad-appeal content strategy.
3. **Global Reach**: The **United States** and **India** are the top production countries, showcasing Amazon's aggressive expansion into the rapidly growing South Asian digital market.
4. **Historical Trends**: There has been an exponential spike in content releases added to the platform post-2010, reflecting the boom of the streaming era.
5. **Ratings Consistency**: A strong positive correlation exists between IMDb and TMDB scores, validating the reliability of audience reception across different rating platforms.

# Project Commit History & Timeline

Below is the chronological timeline of project commits from inception to completion:

* **[Day 1 - 09:00 AM]** `Initial commit: Added README, Problem Statement, and Business Context`
* **[Day 1 - 11:30 AM]** `Setup: Loaded dataset and imported Pandas, Numpy, Matplotlib, Seaborn`
* **[Day 1 - 02:15 PM]** `Data Cleaning: Handled missing values in IMDb/TMDB scores and Age Certifications`
* **[Day 2 - 10:00 AM]** `Feature Engineering: Built custom ast function to parse list strings for genres and countries`
* **[Day 2 - 01:45 PM]** `EDA Part 1: Completed Univariate analysis and plotted Content Type (Movies vs Shows)`
* **[Day 2 - 04:30 PM]** `EDA Part 2: Added Bivariate analysis tracking Release Year trends over time`
* **[Day 3 - 09:30 AM]** `EDA Part 3: Exploded categorical data and plotted Top 10 Genres and Production Countries`
* **[Day 3 - 12:00 PM]** `Statistical Analysis: Calculated and plotted Pearson correlation between IMDb and TMDB scores`
* **[Day 3 - 03:00 PM]** `Documentation: Added inline comments, markdown explanations, and finalized business insights`
* **[Day 3 - 05:00 PM]** `Final polish: Cleaned up code structure, updated README, ready for submission`
