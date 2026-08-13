# Movie Recommendation System

## 1. Project Overview

This project implements a content-based Movie Recommendation System using the TMDB 5000 Movie Dataset.

The system recommends movies based on the similarity between movie features such as genres, keywords, overview, and cast.

## 2. Objective

The objective of this project is to build a simple content-based recommendation system that recommends movies similar to a movie selected by the user.

## 3. Dataset

The project uses the TMDB 5000 Movie Dataset.

Files used:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

The movie dataset contains information such as:

- Movie title
- Genres
- Keywords
- Overview

The credits dataset contains cast information.

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 5. Methodology

The recommendation system follows these steps:

1. Load the TMDB datasets.
2. Merge the movie and credits datasets.
3. Select relevant movie features.
4. Handle missing values.
5. Extract genres, keywords, and cast information.
6. Combine the selected features into a `tags` column.
7. Convert the text features into numerical vectors using TF-IDF.
8. Calculate Cosine Similarity between movies.
9. Create a recommendation function.
10. Return the most similar movies for a selected movie.

## 6. Recommendation Approach

This project uses a content-based filtering approach.

The recommendation system compares the content/features of movies rather than relying on user ratings.

TF-IDF is used to represent the movie tags numerically.

Cosine Similarity is then used to calculate how similar two movies are.

## 7. Example

For example, if the user enters:

`Avatar`

the system returns a list of movies that have similar feature information.

The similarity score is also displayed for each recommendation.

## 8. Results

The project generates:

- Prepared movie dataset
- Sample movie recommendations
- Avatar recommendation results
- Recommendation similarity visualization

The results are stored in the `results` folder.

## 9. Project Structure

Task4_Movie_Recommendation/

├── dataset/

│   ├── tmdb_5000_movies.csv

│   └── tmdb_5000_credits.csv

├── notebooks/

│   └── Movie_Recommendation.ipynb

├── results/

│   ├── movies_prepared.csv

│   ├── avatar_recommendations.csv

│   ├── avatar_recommendations.png

│   └── sample_recommendations.csv

└── README.md

## 10. Conclusion

The project demonstrates how a content-based recommendation system can be developed using movie metadata.

By combining movie features, TF-IDF vectorization, and Cosine Similarity, the system can identify and recommend movies with similar characteristics.