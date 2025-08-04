# netflix-powerbi-dashboard
A data visualization project using power BI to explore netflix movies and tv shows from a kaggle dataset
Netflix Movies and TV Shows – Excel & Power BI Analysis
# Data content
This repository contains data cleaning, visualization, and dashboard reporting of Netflix Movies and TV Shows using Microsoft Excel and Power BI.
Dataset Info
Source: Kaggle - Netflix Movies and TV Shows
File Used: netflix_titles.csv
# Key columns
Key Columns:
show_id: Unique ID
type: Movie or TV Show
title, director, cast
country, date_added, release_year
rating, duration, listed_in (genres)
description
# Data cleaning
Data Cleaning (Excel)
Removed blanks and duplicates
Split multi-value fields (like cast, genres) where needed
Handled nulls in director, country, and date_adde
Converted date_added to standard date format
Created helper columns: Year, Month, Duration (in mins or seasons)
Power BI Visualizations
Power BI Dashboard Includes:
Movie vs TV Show count
Top 10 Countries by content
Content added per Year
Top Ratings (TV-MA, PG, etc.)
Top Directors and Actors
Popular Genres
Content Duration Analysis
Folder Structure
bash
# Code
Copy code
netflix-powerbi-excel/
│
├── netflix_titles.csv            # Raw Dataset
├── netflix_cleaned.xlsx          # Cleaned Excel File
├── Netflix_Dashboard.pbix        # Power BI Report File
└── README.md                     # Project Description
Requirements
Microsoft Excel (2016 or later recommended)
Power BI Desktop
