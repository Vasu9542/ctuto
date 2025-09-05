# 🎬 Content-Based Movie Recommendation System

This project implements a **content-based movie recommender system** using **TF-IDF vectorization** and **cosine similarity**.  
It analyzes movie metadata (genres, keywords, overviews, directors) and recommends movies with the most similar content.  

---

## 🚀 Features
- Preprocesses and cleans movie metadata using **NLTK**.
- Generates a **WordCloud** of most common words in the dataset.
- Uses **TF-IDF Vectorizer** to convert text into numerical features.
- Computes **cosine similarity** to measure closeness between movies.
- Provides **top N movie recommendations** based on user input.

---

## 📂 Dataset
The project uses the **TMDB 5000 Movies dataset** (4,803 movies, 24 columns).  
Key columns used:
- `genres`
- `keywords`
- `overview`
- `title`
- `director`

After cleaning and filtering, the dataset contains **4,383 movies**.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas, NumPy** – Data handling
- **NLTK** – Text preprocessing
- **Scikit-learn** – TF-IDF, cosine similarity
- **Matplotlib, WordCloud** – Data visualization

---


