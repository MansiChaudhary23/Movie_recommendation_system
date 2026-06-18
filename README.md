# Movie_recommendation_system
A content-based movie recommendation system built using Python, Pandas, NumPy, and Scikit-Learn. The system recommends movies similar to a user's selected movie by analyzing features such as genres, keywords, cast, and crew from the TMDB movie dataset.

# Project Overview
This project uses content-based filtering to recommend movies based on similarity scores calculated from movie metadata. The recommendation engine helps users discover movies with similar themes, genres, and casts.

# Features
1)Movie recommendation based on selected movie

2)Content-based filtering approach

3)Data preprocessing and feature engineering

4)Cosine similarity calculation

5)Fast recommendation generation

6)Uses TMDB movie dataset

# Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Jupyter Notebook / Google Colab

# Dataset
The project uses:
1)movies.csv
2)credits.csv

Dataset contains:

1)Movie titles

2)Genres

3)Keywords

4)Cast information

5)Crew information

6)Overview and metadata

# Working Process

1)Load movie and credits datasets.

2)Merge datasets using movie ID.

3)Extract important features:

       a) Genres
       
       b) Keywords
       
       c) Cast
       
       d) Director
       
4)Clean and preprocess data.

5)Create tags by combining features.

6)Convert text into vectors using CountVectorizer.

7)Calculate cosine similarity.

8)Recommend top similar movies.

# Example Recommendation
Input:
The Dark Knight

Output:
Batman Begins,
The Dark Knight Rises,
Man of Steel,
Batman v Superman,
Watchmen
