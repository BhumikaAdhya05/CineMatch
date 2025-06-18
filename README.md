# CineMatch
Content-based Movie Recommendation System using cosine similarity and TF-IDF to suggest similar movies based on input preferences.

# 🎬 Movie Recommendation System

This project is a Content-Based Movie Recommendation System built using Python. It utilizes Natural Language Processing techniques like TF-IDF vectorization and cosine similarity to recommend movies similar to a given title. The model is trained on movie metadata and plots to provide relevant suggestions.

---

## 🚀 Features

- Recommends similar movies based on input title
- Uses TF-IDF Vectorizer on movie descriptions
- Cosine Similarity used for scoring relevance
- Lightweight and easy to run in Jupyter Notebook or Colab
- Uses pandas, scikit-learn, and NLTK

---

## 📁 Dataset Used

The dataset contains:
- Movie titles
- Genres
- Descriptions/Overviews
- Other metadata (for potential future improvement)

Ensure the dataset CSV is named appropriately and located in the same directory or adjust the file path in the notebook accordingly.

---

## ⚙️ Technologies

- Python 3
- Pandas
- NumPy
- Scikit-learn
- NLTK (for optional text preprocessing)
- Jupyter Notebook / Google Colab

---

## 🧠 How It Works

1. **Data Cleaning**: Handles missing values and prepares textual data.
2. **Text Vectorization**: Applies TF-IDF vectorizer on the movie overview/plot.
3. **Similarity Computation**: Uses cosine similarity to find most relevant movie suggestions.
4. **Recommendation Function**: Returns top N similar movie titles for a given input.

---

## ▶️ Usage

1. Clone this repository or open in Colab.
2. Upload or link your dataset (CSV).
3. Run all cells in order.
4. Call the `recommend(movie_name)` function with your desired title.

Example:
```python
recommend("The Matrix")

