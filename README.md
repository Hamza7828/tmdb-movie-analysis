# tmdb-movie-analysis
End-to-end data collection, cleaning, and EDA project using TMDB API

# 🎬 TMDB Top Movies Analysis

An end-to-end Data Science project analyzing top-rated movies fetched directly from the TMDB REST API.

## Project Overview
This project extracts live movie data via TMDB API, cleans and structures it into a Pandas DataFrame, exports it to CSV, and performs Exploratory Data Analysis (EDA) to uncover rating and popularity trends.

## Tech Stack
- **Language:** Python
- **API Fetching:** `requests`, REST API
- **Data Manipulation:** `pandas`
- **Data Visualization:** `seaborn`, `matplotlib`
- **Environment:** Google Colab (Secrets Manager for Security)

## Key Insights
- **Rating Concentration:** The majority of top-rated movies lie within the `8.2` to `8.3` rating bracket.
- **Vote Count Trends:** Movies with extreme high ratings (>8.8) often have fewer vote counts, whereas mainstream popular blockbusters gather significantly higher total votes in the `8.2`–`8.4` range.

## Security
API keys are handled via Colab's internal Secrets manager (`google.colab.userdata`) to prevent authorization keys from being exposed publicly.
