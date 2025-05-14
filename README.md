# 🎬 Movie Recommendation System

This is a content-based movie recommendation system built using Python and TF-IDF vectorization. It recommends similar movies based on the description (overview) of a given movie using natural language processing techniques.

## 📌 Project Overview

- 📁 Dataset: TMDB 5000 Movie Dataset (from Kaggle)
- ⚙️ Technique: TF-IDF Vectorizer + Cosine Similarity
- 📊 Output: Top N similar movies based on textual description
- 💻 Environment: Google Colab / Jupyter Notebook

---

## 🚀 How It Works

1. Load the movie dataset containing titles and overviews
2. Use TF-IDF to convert overviews to numerical vectors
3. Calculate cosine similarity between movies
4. Recommend top N most similar movies to a given title

---

## 🧠 Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Programming Language |
| pandas | Data Handling |
| scikit-learn | TF-IDF + Similarity |
| Google Colab | Notebook Environment |

---

## 📂 Files Included

| File | Description |
|------|-------------|
| movie_recommendation_colab.ipynb | Main notebook with full code |
| tmdb_5000_movies.csv | Dataset (upload manually in Colab) |
| inception_recommendations.csv | Sample output file (optional) |
| README.md | Project description |

---

## 🧪 How to Run

1. Open the notebook in Google Colab:  
   https://colab.research.google.com

2. Upload the dataset file (tmdb_5000_movies.csv)

3. Run all cells in the notebook

4. Call the function:
```python
recommend("Inception", 5)
