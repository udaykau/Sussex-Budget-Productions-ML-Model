# Sussex Budget Production: IMDB Data Analysis

This project analyzes historical IMDB movie data to recommend the most profitable film genre for Sussex Budget Production House, focusing on maximizing profit within a constrained budget.

## Overview

The analysis leverages the IMDB movie metadata to:
- Clean and preprocess the dataset
- Explore relationships between budget, gross, profit, and genre
- Identify the most profitable genres and directors
- Perform hypothesis testing to validate findings

The final recommendation is based on statistical evidence and exploratory data analysis, with a focus on genres that offer high returns for a budget of up to 1.5 million GBP.

## Features

- Data cleaning: Handles missing values, removes duplicates, and drops irrelevant columns
- Exploratory Data Analysis (EDA): Visualizes distributions, relationships, and genre frequencies
- Profitability Analysis: Calculates profit percentages and identifies top-performing genres and movies
- Statistical Testing: Uses Welch’s t-test to compare profits across genres
- Data-driven Recommendation: Suggests the optimal genre for production investment

## Requirements

- Python 3.12+
- pandas
- numpy
- matplotlib
- seaborn
- scipy

Install dependencies with:
```sh
pip install pandas numpy matplotlib seaborn scipy
