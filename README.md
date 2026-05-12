# Netflix Data Analysis (Python Project)

Exploratory Data Analysis project using Python and visualization libraries.

## Project Overview
This project performs exploratory data analysis (EDA) on the Netflix Titles dataset using Python. The analysis focuses on identifying trends, content distribution, genre popularity, ratings, and country-wise content production on Netflix.

## Objectives
- Analyze distribution of Movies vs TV Shows
- Identify top content-producing countries
- Understand content growth over years
- Explore rating distribution
- Discover most popular genres
- Perform statistical analysis on Netflix content
- Analyze distribution of release years
- Calculate mean and median release year
- Explore correlation between numeric features


## Dataset
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
│   └── netflix_titles.csv
│
├── notebook/
│   └── netflix_analysis.ipynb
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

### 6. Distribution Analysis
Analyzed the distribution of Netflix release years.

### 7. Statistical Analysis
Calculated mean and median values for release years.

### 8. Correlation Analysis
Explored relationships between numeric features using correlation heatmap.

## Statistical Analysis

The project also includes statistical analysis to better understand Netflix content patterns.

### Analysis Performed
- Distribution analysis of release years
- Distribution analysis of movie durations
- Mean and median calculations
- Correlation analysis using heatmap visualization

### Statistical Insights
- Most Netflix content belongs to modern release years
- Movie durations are concentrated around standard industry runtime
- Mean and median values are relatively close, suggesting balanced distributions
- Numeric features show weak correlation with each other

## Key Insights
- Movies dominate Netflix compared to TV Shows
- USA is the largest content contributor
- Netflix content increased significantly after 2015
- TV-MA is the most common rating
- Drama and Comedy are the most popular genres
- Most Netflix content was released after 2000
- Most movies are between 80–120 minutes long
- Mean and median release years are relatively close, indicating balanced distribution
- Correlation between numeric features is weak
