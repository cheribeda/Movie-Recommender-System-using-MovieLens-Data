
# Movie Recommender System

## Overview
This project demonstrates a simple movie recommender system using collaborative filtering with cosine similarity. It uses the MovieLens 100k dataset to suggest movies based on user rating patterns.

## Data Sources
- [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
- Contains three CSV files: `movies.csv`, `ratings.csv`, and `links.csv` hosted on GitHub.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Methodology
1. **Data Merging**: Combined movie titles with user ratings.
2. **Matrix Creation**: Created a user-movie matrix with movie titles as columns and user IDs as rows.
3. **Similarity Calculation**: Used `cosine_similarity` to calculate how similar each movie is to others.
4. **Recommendation Function**: Defined a function that, given a movie title, returns the top 10 similar movies based on cosine similarity scores.

## Example Output
Given the movie **"Amityville Horror, The (1979)"**, the recommender system suggested:
- Friday the 13th Part IV: The Final Chapter (1984)
- Child's Play (series)
- Christine (1983)
- Amityville sequels and spin-offs
- Poltergeist II: The Other Side (1986)

## How to Run
Open the Jupyter Notebook file and run each cell. You can change the movie title in the `get_recommendations()` function to explore other recommendations.

## References
- Harper & Konstan (2015) on MovieLens datasets  
- Pedregosa et al. (2011) on scikit-learn  
- McKinney (2010) on pandas
