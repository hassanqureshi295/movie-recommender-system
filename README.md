# Movie Recommendation System

## Overview
This repository contains a content-based movie recommendation system developed in Python. The system utilizes data from TMDb (The Movie Database) to recommend movies similar to a selected movie. It employs various natural language processing techniques, including tokenization, stemming, and vectorization, to create feature vectors that are then used to calculate similarities between movies.

## Features
- **Data Merging**: Combines movie metadata with credit data.
- **Data Cleaning**: Handles missing values, duplicates, and processes textual data for analysis.
- **Feature Extraction**: Extracts and processes key information such as genres, keywords, cast, and crew.
- **Text Vectorization**: Uses `CountVectorizer` to convert textual data into numerical vectors.
- **Similarity Calculation**: Implements cosine similarity to find and rank movies based on their similarity to the input movie.
- **Movie Recommendations**: Provides top movie recommendations based on the similarity scores.
