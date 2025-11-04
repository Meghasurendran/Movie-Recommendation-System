🎬 Content-Based Movie Recommendation System

This project builds a content-based movie recommendation system using machine learning and natural language processing (NLP).
It recommends movies based on their genres, keywords, cast, crew, and plot descriptions, providing personalized suggestions through content similarity.

🚀 Project Overview

This system analyzes movie metadata to recommend similar movies.
It uses TF-IDF Vectorization and Cosine Similarity to calculate how closely related different movies are based on their textual features.

🧩 Features

. Extracts and processes movie data (genres, keywords, cast, crew, overview)

. Creates a combined tags column for text-based similarity

. Uses TF-IDF Vectorizer to transform text into numerical features

. Calculates similarity using Cosine Similarity

. Recommends the top 5 movies most similar to a given title

. Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, NLTK, Ast

Visualization: Matplotlib, Seaborn (if used for EDA)

Dataset: TMDB 5000 Movies Dataset

📂 Dataset

This project uses the TMDB 5000 Movies Dataset from Kaggle.
Download both tmdb_5000_movies.csv and tmdb_5000_credits.csv and place them in the data folder.
