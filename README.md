# 🎬 Movie Recommendation System

## Overview

This project implements a Content-Based Movie Recommendation System using Natural Language Processing (NLP) and Machine Learning techniques.

The recommendation engine analyzes movie descriptions and recommends similar movies using TF-IDF Vectorization and Cosine Similarity.

Given a movie title, the system returns a list of movies with similar content and themes.

---

## Features

* Content-Based Movie Recommendations
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Cosine Similarity Search
* Exploratory Data Analysis (EDA)
* Model Serialization using Pickle
* Reproducible Training Pipeline

---

## Dataset

TMDB 5000 Movie Dataset

Files Used:

* tmdb_5000_movies.csv
* tmdb_5000_credits.csv

Dataset contains:

* Movie Titles
* Plot Overviews
* Genres
* Keywords
* Cast Information
* Crew Information
* Ratings and Popularity Metrics

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

### Machine Learning Techniques

* TF-IDF Vectorization
* Cosine Similarity
* Content-Based Recommendation Systems

---

## Project Workflow

### 1. Data Collection

Loaded movie and credits datasets from TMDB.

### 2. Data Preprocessing

* Merged movie and credit datasets
* Removed missing values
* Selected relevant features
* Cleaned textual data

### 3. Feature Engineering

Created textual feature representations from movie overviews.

### 4. Vectorization

Converted movie descriptions into numerical vectors using TF-IDF.

### 5. Similarity Calculation

Computed pairwise movie similarity using Cosine Similarity.

### 6. Recommendation Engine

Generated recommendations based on similarity scores.

---

## Example

Input:

Interstellar

Output:

* The Martian
* Gravity
* Arrival
* Contact
* Moon

(Recommendations may vary depending on preprocessing.)

---

## Repository Structure

movie-recommendation-system/

├── data/

│   ├── tmdb_5000_movies.csv

│   └── tmdb_5000_credits.csv

├── notebooks/

│   └── recommendation_system.ipynb

├── results/

├── README.md

├── requirements.txt

└── .gitignore

---

## Model Files

Serialized model files are hosted separately on [Hugging Face](https://huggingface.co/CyborgC/movie-recommendation-system) due to repository size considerations.

The notebook can regenerate all model artifacts locally.

---

## Key Learnings

* Natural Language Processing
* Feature Engineering
* Similarity Search
* Recommendation Systems
* Machine Learning Workflows
* Data Analysis and Visualization

---

## Future Improvements

* Include Genres in Recommendations
* Include Keywords
* Include Cast Information
* Include Director Information
* Hybrid Recommendation System
* Streamlit Web Application
* TMDB API Integration for Posters

---

## Author

Built as a Machine Learning and NLP portfolio project.
