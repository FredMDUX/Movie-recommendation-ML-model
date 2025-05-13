# 🎬 Movie Recommendation System

This project builds a hybrid movie recommendation system using collaborative filtering (user-based and item-based), content-based filtering (TF-IDF on genres), and a hybrid ensemble. The system is evaluated using RMSE, Precision@10, Recall@10, and SHAP-based interpretability.

## 🚀 Features

- Predicts user ratings using multiple recommendation algorithms
- Recommends top-N movies with ranking and relevance metrics
- Addresses cold-start problems through genre metadata
- Visual analysis of results and feature importance (SHAP)

## 📁 Project Structure

- `movie_recommendation_system.ipynb` – Main Colab notebook
- `data/` – Folder for dataset files (ratings.csv, movies.csv, etc.)
- `plots/` – Visual output folder (charts, SHAP plots)
- `README.md` – This documentation

## 🛠️ Dependencies

Ensure Python 3.10+ is installed. Required packages include:

```bash
pip install pandas numpy scikit-learn surprise shap matplotlib seaborn
🧪 Setup & Usage
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
Download the dataset

Place the following files in the data/ folder. Download from MovieLens 100K.

ratings.csv

movies.csv

tags.csv

genome_scores.csv

genome_tags.csv

links.csv

## Run the notebook

Open movie_recommendation_system.ipynb in Google Colab or Jupyter Notebook. Follow the step-by-step code to preprocess data, build models, evaluate, and visualize results.

## 📊 Sample Outputs
RMSE Comparison

Precision vs Coverage

SHAP Summary for Genre Features

📌 Notes
The runtime may be long due to dataset size and similarity computations.

Consider exploring faster alternatives like LightFM, Faiss, or dimensionality reduction methods for production-scale deployment.

📄 License
This project is for academic and educational use only.
