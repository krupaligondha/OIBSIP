# 📱 Google Play Store Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Google Play Store ecosystem to understand app categories, ratings, installs, pricing, and user sentiment.

## 🎯 Objectives

- Clean and preprocess Play Store app and review datasets
- Analyze app distribution across categories
- Study ratings and category-wise performance
- Analyze app size and installation trends
- Compare free and paid applications
- Estimate revenue by category
- Perform sentiment analysis on user reviews
- Identify positive and negative sentiment by category
- Generate data-driven insights for app developers

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob / VADER
- Plotly
- Jupyter Notebook

## 🧹 Data Cleaning

The project includes:

- Handling missing values
- Removing duplicate apps
- Correcting data types
- Converting `Installs` from strings such as `"10,000+"` to numerical values
- Cleaning price and size columns
- Preparing user reviews for sentiment analysis

## 📊 Analysis & Visualizations

The project includes:

- App Distribution by Category
- Rating Distribution
- Average Rating by Category
- App Size vs. Installs
- Free vs. Paid Apps
- Price Distribution
- Estimated Revenue by Category
- Sentiment Distribution
- Sentiment by App Category
- Interactive Plotly Visualization

## 💬 Sentiment Analysis

User reviews are classified into:

- **Positive**
- **Negative**
- **Neutral**

Sentiment analysis is performed using **TextBlob or VADER**.

The analysis also identifies which app categories receive the most positive and negative user feedback.

## 💡 Key Insights

The analysis helps understand:

- Which categories are highly saturated
- What types of apps receive higher ratings
- Relationship between app size and installs
- Pricing patterns of paid applications
- Categories with higher estimated revenue
- User satisfaction and sentiment across categories

## 🚀 Business Recommendations

Based on the analysis, developers can:

1. Identify less-saturated categories with growth opportunities.
2. Focus on features and user experience that improve ratings and sentiment.
3. Use pricing and category revenue trends to develop an appropriate monetization strategy.

## 📁 Project Structure

```text
DataAnalytics-L2-GooglePlayStoreAnalysis/
│
├── OIBSIP Level 2 Task-4 Google Play Store Analysis.ipynb
├── googleplaystore.csv
├── googleplaystore_user_reviews.csv
└── README.md
