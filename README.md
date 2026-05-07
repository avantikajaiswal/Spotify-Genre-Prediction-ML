# Spotify Genre Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning to predict Spotify music genres using audio features such as:
- Danceability
- Energy
- Loudness
- Tempo
- Acousticness
- Valence
- Speechiness
- Instrumentalness

The project performs a comparative analysis of genre classification complexity using:
- 114 Genre Classification
- Top 50 Genre Classification
- Top 25 Genre Classification
- Top 10 Genre Classification

The main objective is to study how reducing genre complexity affects machine learning model accuracy and performance.


## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset Information

- Dataset: Spotify Tracks Dataset
- Total Records: 114,000
- Total Genres: 114
The dataset contains Spotify track audio features and genre labels used for supervised learning classification.

## Machine Learning Workflow

The project follows the complete Machine Learning pipeline:
1. Data Loading
2. Data Cleaning
3. Feature Selection
4. Train-Test Splitting
5. Random Forest Classification
6. Model Evaluation
7. Comparative Analysis
8. Visualization

## Features Used for Prediction

The following audio features were used for genre prediction:
- popularity
- duration_ms
- danceability
- energy
- key
- loudness
- mode
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo
- time_signature

## Model Performance Comparison

| Genre Classes | Accuracy |
|---|---|
| 114 Genres | 32.09% |
| 50 Genres | 43.8% |
| 25 Genres | 59.28% |
| 10 Genres | 64.0% |

## Key Insights

- Reducing the number of genres improved model accuracy significantly.
- Higher genre counts increased classification complexity and genre overlap.
- The Top 10 Genre model achieved the best performance with 64% accuracy.
- Random Forest performed effectively for multiclass music genre classification.

## Model Evaluation

The project includes:
- Accuracy Evaluation
- Confusion Matrix Visualization
- Comparative Accuracy Analysis

Confusion Matrix visualization was primarily used for the Top 10 Genre model because higher-class confusion matrices become extremely large and difficult to interpret visually.

ROC Curves were not used because multiclass ROC visualizations for large genre counts become highly complex and less meaningful for this project.

## Future Improvements

The project can be further improved using:
- XGBoost
- Neural Networks
- Hyperparameter Tuning
- Feature Engineering
- Deep Learning Audio Models
- Real-time Genre Prediction Systems

## Conclusion

* This project successfully implemented supervised machine learning techniques for Spotify genre prediction and demonstrated how classification complexity affects model performance.
* The comparative analysis across 114, 50, 25, and 10 genres provided valuable insights into multiclass classification behavior and predictive modeling performance.
