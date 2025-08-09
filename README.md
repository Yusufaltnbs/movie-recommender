# 🎬 Movie Recommender System | TMDB 5000 Dataset

This project is a **Movie Recommendation System** developed using the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) from **Kaggle**.  
The system recommends movies similar to the one selected by the user based on **genre, cast, director, and keywords**.

---

## 📌 Features
- **Content-Based Filtering** approach
- Similarity calculation using **TF-IDF** and **Cosine Similarity**
- Suggests the top 5 most similar movies when a movie name is entered
- TMDB API integration for movie posters
- Easy-to-use **Streamlit** interface

---

## 📂 Dataset
- **Source:** [Kaggle - TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- **Files:**
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

The dataset contains:
- Movie title, genres, cast, director, description, etc.
- Text data necessary for calculating similarity between movies.

---

## ⚙️ Technologies Used
- **Python** (pandas, numpy, scikit-learn)
- **Streamlit** (web UI)
- **Requests** (TMDB API requests)
- **Pickle** (model and data storage)

---

## 🚀 Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/username/movie-recommender-tmdb.git
cd movie-recommender-tmdb

streamlit run app.py

The file similarity.pkl is not included in this repository due to its large size.
To run the application, you will need to generate this file locally using the preprocessing script included in the project.
