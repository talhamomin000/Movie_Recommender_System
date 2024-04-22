# Movie Recommendation System

This is a content based movie recommendation system built using Python, Jupyter Notebook, and Streamlit.

## Overview

This project aims to recommend similar movies based on user input. It utilizes natural language processing techniques to extract features from movie descriptions, genres, keywords, cast, and crew. The recommendation is made using cosine similarity between movie features.

## How it Works

1. **Data Preparation:**
   - Data is loaded from two CSV files: `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`.
   - Features like movie title, overview, genres, keywords, cast, and crew are processed and engineered.
   -  Dataset link:- https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

2. **Model Building:**
   - Text data is vectorized using CountVectorizer.
   - Cosine similarity is computed between movie tags to build the recommendation model.

3. **Streamlit Web App:**
   - The recommendation system is deployed as a web app using Streamlit.
   - Users can select a movie from a dropdown menu.
   - Clicking on the "Show Recommendation" button displays similar movies with posters.
  
   ![image](https://github.com/talhamomin000/Movie_Recommender_System/assets/121718008/4ef66db1-4349-480b-b756-c605601b7ef4)



