# 🎬 Movie Recommendation System

A Content-Based Movie Recommendation System that recommends similar movies based on their content features such as genres, keywords, cast, crew, and overview. The recommendation engine uses **CountVectorizer**, **TF-IDF Vectorizer**, and **Cosine Similarity** to identify movies with similar content.

---

## 🚀 Features

* Content-Based Movie Recommendation
* Movie similarity using Cosine Similarity
* Text vectorization with CountVectorizer and TF-IDF Vectorizer
* Clean data preprocessing and feature engineering
* Built and tested in Google Colab

---

## 🛠️ Tech Stack

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* CountVectorizer
* TF-IDF Vectorizer
* Cosine Similarity
* Pickle

---

## 📂 Dataset

The project uses the **TMDB Movie Dataset**, which includes:

* Movie Title
* Genres
* Keywords
* Cast
* Crew
* Overview

---

## ⚙️ Project Workflow

1. Load the TMDB movie dataset.
2. Clean and preprocess the data.
3. Merge important features into a single text column.
4. Convert text into vectors using CountVectorizer and TF-IDF Vectorizer.
5. Calculate movie similarity using Cosine Similarity.
6. Recommend the most similar movies based on the selected movie.

---

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np
from sklearn.feature_extraction.text import CountVectorizer, TfidfVectorizer
from sklearn.metrics.pairwise import cosine_similarity
import pickle
```

---

## 📈 Future Improvements

* Deploy using Streamlit
* Integrate TMDB API for movie posters and details
* Add Hybrid Recommendation System
* Improve recommendations using Deep Learning

---

## ▶️ Environment

This project was developed and executed using **Google Colab**, making it easy to run without any local setup.

---

## 👨‍💻 Author

**Satyam Mishra**

⭐ If you found this project helpful, consider starring the repository.
