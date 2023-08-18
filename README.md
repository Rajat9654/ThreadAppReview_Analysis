# ThreadAppReview_Analysis

## Introduction

This analysis delves into app review data to extract insights on user sentiments, preferences, and trends. Focused on a Thread app, aimed to unearth valuable patterns to optimize user experience and app performance.

## Dataset Overview

The dataset includes:

- review_id: Unique identifier
- user_name: Review contributor's name
- review_title: Review title
- review_description: Detailed review
- rating: User's numeric rating
- thumbs_up: Count of positive votes
- review_date: Submission date
- developer_response: App developer's responses
- developer_response_date: Developer's response date
- appVersion: App version
- laguage_code: Language code
- country_code: User's country code

## Data Source

Kaggle: [Dataset Link](https://www.kaggle.com/datasets/shuvammandal121/37000-reviews-of-thread-app-dataset/discussion)
Date Range: 2023-07-06 to 2023-08-08

## Exploratory Data Analysis (EDA)

Initial steps in Python involved:

1. Basic data overview
2. Removal of CSV index column
3. Source comparison (Google Play dominates)
4. Rating distribution (5-star dominant)
5. Rating distribution by source (different trends)
6. Developer response analysis (minimal)
7. Language & country focus (English, US)
8. Thumbs Up vs. Rating (peak at 3)
9. Average rating over time (initial high then drop)

## Word Cloud Analysis

To highlight commonly used words in titles.

## Sentiment Analysis

TextBlob used for sentiment analysis on review_description. Key findings:

1. Positive Sentiments: Majority of reviews positive, indicating user satisfaction.
2. Negative Sentiments: Few reviews expressed negative sentiment, often related to issues or bugs.

## Conclusion

### EDA

1. Early adopters: Android users led by review counts and possible downloads.
2. 5-star Love: Initial ratings predominantly 5 stars.
3. App Store Insight: App Store skewed towards 1-star, potential UI and feature issues.
4. Developer Involvement: Minimal developer responses.
5. Thumbs Up: Positive overall sentiment.
6. Time Trend: Initial high ratings dropped to an average of 3 over time.

### Word Cloud Analysis

1. Rivalry: Words like Twitter, Instagram, Facebook suggest competition.
2. Positivity: Keywords like good, great, better indicate overall app quality.

### Sentiment Analysis

More than 80% of users found the app satisfying.

## Future Analysis

Recommendation for advanced techniques like topic modeling, sentiment analysis on developer responses, and app update impact analysis for deeper insights.
