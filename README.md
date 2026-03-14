# Movie Recommendation System

This project is a **content-based movie recommendation system** built using Python.
It recommends movies similar to the one selected by the user based on movie metadata such as **genres, keywords, cast, and director**.

The system processes the **TMDB 5000 Movies Dataset** and generates recommendations by analyzing similarities between movies.

---

## Features

* Recommends similar movies based on content
* Uses movie metadata such as:

  * Genres
  * Keywords
  * Cast
  * Director
* Data preprocessing and feature extraction
* Similarity-based recommendation logic

---

## Dataset

The project uses the **TMDB 5000 Movies Dataset** which contains information about thousands of movies including:

* Movie title
* Overview
* Genres
* Cast
* Crew
* Keywords

Files used:

* `tmdb_5000_movies.csv`
* `tmdb_5000_credits.csv`

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

```
movie-recommendation-system
│
├── app.py
├── movie_recommendation_model.ipynb
└── README.md
```

---

## How It Works

1. Load movie and credit datasets
2. Merge datasets based on movie title
3. Select relevant features such as genres, keywords, cast, and crew
4. Clean and preprocess text data
5. Extract metadata such as director and main cast
6. Combine features to create movie tags
7. Use similarity techniques to recommend movies similar to a given movie

---

## How to Run

Clone the repository

```
git clone https://github.com/Nikhil-Narwade/movie-recommendation-system.git
```

Open the notebook

```
movie_recommendation_model.ipynb
```

Run all cells to preprocess the dataset and generate recommendations.

---

## Future Improvements

* Add a web interface using Streamlit
* Deploy the application online
* Improve recommendation accuracy using advanced NLP techniques

---

## Author

**Nikhil Narwade**
