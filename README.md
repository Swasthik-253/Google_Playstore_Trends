# Google_Playstore_Trends

## Overview
This project analyzes the Google Play Store dataset to uncover insights about app performance, user sentiments, and category trends. The analysis focuses on identifying high-performing categories, trends in user ratings and installs, and sentiment distribution across app reviews. 

## Objective
The goal is to:
1. Understand app performance metrics such as ratings, installs, and reviews.
2. Analyze sentiment trends in user reviews.
3. Provide actionable insights for app developers and marketers.

## Features
- **Data Cleaning**: Preprocessed fields such as `Size`, `Installs`, `Price`, and `Rating`.
- **Exploratory Data Analysis**: Visualized app performance by categories, ratings, and installs.
- **Sentiment Analysis**: Used VADER sentiment analysis to classify reviews into Positive, Neutral, and Negative.
- **Correlation Analysis**: Explored relationships between app size, ratings, and reviews.

## Tools and Technologies
- **Python Libraries**: 
  - `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
  - `nltk` for sentiment analysis.
- **Dataset**: Google Play Store and User Reviews datasets (from Kaggle).

## Key Insights
1. **Category Performance**:
   - `Health & Fitness` and `Education` apps consistently received high ratings.
   - `Family` and `Game` categories had the highest app counts but showed varied ratings.

2. **Sentiment Trends**:
   - Positive sentiments dominated reviews, particularly in `Entertainment` and `Education`.
   - Neutral and negative sentiments highlighted areas for improvement.

3. **Install and Rating Trends**:
   - Free apps had higher install counts but lower average ratings compared to paid apps.
   - Smaller app sizes correlated with better user ratings.

## Visualizations
The project includes:
- Bar charts for top apps by rating and category distribution.
- Scatter plots for installs vs. ratings and app size vs. ratings.
- Stacked bar charts for sentiment distribution by category.
- Heatmaps for correlation analysis.

## Future Work
- Add predictive modeling for app success based on features.
- Expand sentiment analysis with advanced NLP techniques.
- Create an interactive dashboard for real-time insights.
