# movie-data-anlaysis-netflix
The Netflix Movies dataset contains detailed information about movies available on the Netflix platform. It includes features such as movie titles, genres, release dates, popularity scores, vote averages, and more.
# Netflix Movies Data Analysis

## 🎬 Project Overview

This project involves cleaning and analyzing a Netflix movies dataset. The goal was to prepare the data for analysis, explore trends, and gain insights using visualizations.

## 🛠️ Tools & Libraries Used

- **Pandas** – for data manipulation and cleaning  
- **Matplotlib** – for basic visualizations  
- **Seaborn** – for detailed and attractive graphs  

## 🧹 Data Cleaning & Preparation

- Uploaded and read the dataset using Pandas
- Converted the **release date** column into **datetime format**, and extracted **year**
- Removed unnecessary columns that were not useful for analysis
- Dropped duplicate rows to ensure data accuracy
- Modified the **vote_average** column:
  - High votes were labeled as **"Popular"**
  - Low votes were labeled as **"Below Average"**
- Handled the **genre** column:
  - Separated multiple genres listed in a single row into individual rows for better analysis

## 📊 Data Analysis & Visualization

Used various questions and graphs to uncover patterns and trends such as:

- Most popular movie genres
- Number of movies released per year
- Distribution of vote averages
- Genre-wise popularity of movies

## 🔍 Key Insights

- Some genres are more dominant in the dataset (e.g., Drama, Comedy)
- Movie popularity can be linked with vote averages
- A steady increase in movie production over the years
- Multi-genre movies are common and needed to be unstacked for accurate analysis
