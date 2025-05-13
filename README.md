# Movie-recommendation-system
A hybrid movie recommendation system using collaborative filtering and content-based filtering, built with Python, scikit-learn, and Surprise. Includes evaluation metrics and SHAP-based interpretability.

# Movie Recommendation System

This repository contains code for building a hybrid movie recommendation system using:

- User-based and item-based collaborative filtering (Surprise library)
- Content-based filtering (TF-IDF on movie genres)
- A hybrid model combining both approaches
- Evaluation using RMSE, Precision@10, Recall@10
- Interpretability using SHAP

## Files
- `movie_recommendation_system.ipynb` – Main Colab notebook
- `rating.csv`, `movie.csv`, etc. – MovieLens dataset files (if permitted)
- `plots/` – Visuals like SHAP summary, evaluation charts

## Requirements
- Python 3.10+
- pandas, numpy, scikit-learn, surprise, shap, matplotlib, seaborn

## How to Use
1. Upload MovieLens CSV files to `/data` folder.
2. Run all cells in the notebook.
3. Visual outputs and recommendation results will be displayed.
