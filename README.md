# Movies Recommendation System

## Description

This repository contains a Python script for building a simple movie recommendation system using the TF-IDF vectorization and cosine similarity techniques. The script uses NumPy, Pandas, and scikit-learn to process and analyze movie data. With this recommendation system, users can find movies similar to their input, facilitating movie discovery based on content.

## Key Features

1. **Data Processing:** The script utilizes the NumPy and Pandas libraries to load and preprocess movie data, handling missing values efficiently.

2. **Feature Fusion:** It combines various movie features, such as genres, keywords, taglines, cast, and director, into a single feature vector for analysis.

3. **TF-IDF Vectorization:** Using scikit-learn's TF-IDF vectorizer, it transforms the combined feature vectors into numerical values suitable for similarity calculations.

4. **Cosine Similarity:** The system calculates cosine similarity scores between movies, enabling the identification of content-wise similar movies.

5. **User Interaction:** Users can input a movie title, and get name of movies similar to that movie.

## How to Use

1. Clone the repository to your local machine.

2. Run the script and provide the title of the movie you want recommendations for.

3. The system will return a list of recommended movies based on content similarity.

### Example

```python
movie_name = input("Enter the name of the movie: ")
Input: iron man
Result:
1 : Iron Man
2 : Iron Man 2
3 : Iron Man 3
4 : Avengers: Age of Ultron
5 : The Avengers
6 : Captain America: Civil War
7 : Captain America: The Winter Soldier
8 : Ant-Man
9 : X-Men
10 : Made

```

## Dataset:
You can find the dataset [here](https://drive.google.com/file/d/1WsJtJtbNXLfY4SwQxyJVD5yT_oTr_jyH/view?usp=share_link)