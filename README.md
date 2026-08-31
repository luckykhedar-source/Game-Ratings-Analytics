# 🎮 Game Ratings Analytics

## 📌 Project Overview

This project analyzes video game data to understand trends in
game releases, user ratings, genres, and gaming platforms.

The project also applies statistical analysis and machine
learning techniques to identify factors influencing game ratings.

## 🎯 Business Objectives

- Analyze game release trends over time
- Compare user ratings across genres
- Compare ratings across platforms
- Identify top-rated genres and platforms
- Analyze rating trends by decade
- Test whether platform differences are statistically significant
- Identify relationships between release year and user rating
- Build a predictive model for user ratings
- Identify the most influential features

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Scikit-learn
- Jupyter Notebook
- GitHub

## 📂 Dataset

The dataset contains:

- Game Name
- Genre
- Platform
- Release Year
- User Rating

## 🔍 Project Steps

### 1. Data Cleaning

- Missing-value detection
- Duplicate removal
- Anomaly detection
- Genre standardization
- Platform standardization

### 2. Feature Engineering

Created:

- Decade

### 3. Exploratory Data Analysis

Analyzed:

- Games by genre
- Games by platform
- Games by release year
- Average ratings
- Rating distributions
- Top 5 genres
- Top 5 platforms

### 4. Statistical Analysis

Performed:

- Decade-based time-series analysis
- One-way ANOVA
- Pearson correlation

### 5. Machine Learning

Built:

- Random Forest Regression model

Evaluated using:

- MAE
- RMSE
- R²

### 6. Feature Selection

Used:

- Permutation Importance

## 📈 Key Findings

- Survival games had the highest average user rating among genres.
- PC had the highest average user rating among platforms.
- Average ratings varied slightly across decades.
- ANOVA indicated no statistically significant difference
  in ratings across platforms.
- Release Year showed virtually no linear correlation
  with User Rating.
- Genre was the most influential feature among the available
  predictors.
- Genre, Platform, and Release Year alone were insufficient
  for highly accurate rating prediction.

## 🚀 Future Improvements

Additional features could improve the predictive model:

- Sales
- Critic Score
- Number of Reviews
- Developer
- Publisher
- Game Budget
- Playtime
- User Engagement