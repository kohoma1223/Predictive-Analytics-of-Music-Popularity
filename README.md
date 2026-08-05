# Predictive Analytics of Music Popularity

## Overview
This project analyzes over 100,000 Spotify tracks to identify audio characteristics associated with song popularity. Using Python and machine learning techniques, I explored relationships between audio features and popularity and built predictive models to classify and estimate popularity.

## Objective
Investigate whether audio features such as danceability, energy, tempo, valence, and acousticness can predict Spotify track popularity.

---

## Exploratory Data Analysis

### Spotify Popularity Distribution

To understand the distribution of track popularity scores, I analyzed the frequency of songs across different popularity levels. This helped determine the structure of the target variable and informed the creation of popularity categories for classification.

![Popularity Distribution](Popularity_Distribution.png)


### Audio Feature Correlation with Popularity

To understand relationships between audio characteristics and popularity, I calculated correlations between numerical audio features and Spotify popularity scores.

![Feature Correlation](popularity_correlation.png)

The analysis shows which audio features have stronger positive or negative relationships with track popularity.

---

## Predictive Modeling

Two machine learning approaches were used:

### 1. Linear Regression Model
- Predicted continuous Spotify popularity scores using audio features.
- Evaluated performance using R².

### 2. Random Forest Classification Model
- Converted popularity scores into binary categories (high vs. low popularity).
- Predicted popularity groups using audio features.
- Evaluated performance using accuracy, precision, recall, and confusion matrices.

---

## Model Performance Comparison

![Model Comparison](model_comparison.png)

The Random Forest classification model achieved stronger predictive performance compared to the regression approach.

---

## Random Forest Feature Importance

The Random Forest model was used to identify which audio characteristics contributed most to popularity predictions.

![Feature Importance](feature_importance.png)

---

## Classification Evaluation

The confusion matrix below shows the model's ability to correctly classify high and low popularity tracks.

![Confusion Matrix](confusion_matrix.png)

---

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory data analysis
- Machine learning
- Model evaluation
- Data visualization
