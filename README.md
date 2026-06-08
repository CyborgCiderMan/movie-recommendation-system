\# Movie Recommendation System



\## Project Overview



This project implements a Content-Based Movie Recommendation System using Natural Language Processing (NLP) and Machine Learning techniques.



The recommendation engine analyzes movie descriptions and identifies similar movies using TF-IDF Vectorization and Cosine Similarity. Given a movie title, the system returns a list of movies with similar content.



\---



\## Objective



The objective of this project is to build a recommendation engine capable of suggesting movies based on textual similarity between movie descriptions.



\---



\## Dataset



TMDB 5000 Movie Dataset



Files Used:



\* tmdb\_5000\_movies.csv

\* tmdb\_5000\_credits.csv



Dataset contains:



\* Movie Titles

\* Overview / Plot Summary

\* Genres

\* Keywords

\* Cast Information

\* Crew Information



\---



\## Technologies Used



\### Programming Language



\* Python



\### Libraries



\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Scikit-Learn



\### Machine Learning Techniques



\* TF-IDF Vectorization

\* Cosine Similarity

\* Content-Based Recommendation Systems



\---



\## Project Workflow



\### 1. Data Collection



Loaded movie and credits datasets from TMDB.



\### 2. Data Preprocessing



\* Merged datasets

\* Removed missing values

\* Selected relevant features

\* Cleaned textual data



\### 3. Feature Engineering



Created a combined text representation using movie overviews.



\### 4. Vectorization



Converted text into numerical vectors using TF-IDF Vectorizer.



\### 5. Similarity Calculation



Computed pairwise movie similarity using Cosine Similarity.



\### 6. Recommendation Engine



Developed a function that recommends similar movies based on user input.



\---



\## Example



Input:



Interstellar



Output:



\* The Martian

\* Arrival

\* Gravity

\* Contact

\* Moon



(Note: recommendations may vary slightly depending on preprocessing and dataset version.)



\---



\## Results



Successfully developed a recommendation engine capable of identifying and recommending similar movies based on textual features.



The system demonstrates practical applications of:



\* Natural Language Processing

\* Information Retrieval

\* Similarity Search

\* Recommendation Systems



\---



\## Future Improvements



\* Incorporate Genres

\* Incorporate Keywords

\* Incorporate Cast Information

\* Incorporate Director Information

\* Deploy using Streamlit

\* Integrate TMDB API for posters and metadata

\* Hybrid Recommendation System using ratings



\---



\## Repository Structure



movie-recommendation-system/



├── data/



├── notebooks/



├── models/



├── results/



├── README.md



└── requirements.txt



\---



\## Author



Built as a Machine Learning and NLP portfolio project.



