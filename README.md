# Netflix Data Analysis (Python Project)

## Project Overview
This project is a simple exploratory data analysis (EDA) of the Netflix dataset. The goal is to understand trends, patterns, and insights about Netflix content such as movies, TV shows, genres, ratings, and countries.

## Objectives
- Analyze distribution of Movies vs TV Shows
- Identify top content-producing countries
- Understand content growth over years
- Explore rating distribution
- Discover most popular genres

##  Dataset
The dataset used in this project is from Kaggle:

- Netflix Titles Dataset  
- Source: https://www.kaggle.com/datasets/shivamb/netflix-shows

## Tools & Libraries Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- VS Code

## Project Structure
netflix-data-analysis/
│
├── data/
│ └── netflix_titles.csv
│
├── notebook/
│ └── netflix_analysis.ipynb
│
├── venv/
│
├── requirements.txt
├── README.md
└── .gitignore

## Data Cleaning Steps
- Removed unnecessary spaces in text columns
- Handled missing values in key columns
- Converted `date_added` to datetime format
- Extracted `year_added` for time-based analysis
- Dropped rows with invalid date values

## Key Analysis Performed

### 1. Movies vs TV Shows
Analyzed the distribution of content types on Netflix.

### 2. Top Countries
Identified countries producing the most Netflix content.

### 3. Content Over Time
Studied how Netflix content has grown over the years.

### 4. Ratings Distribution
Explored the most common content ratings.

### 5. Top Genres
Found the most popular genres on Netflix.

## Key Insights
- Movies dominate Netflix compared to TV Shows
- USA is the largest content contributor
- Netflix content increased significantly after 2015
- TV-MA is the most common rating
- Drama and Comedy are the most popular genres
