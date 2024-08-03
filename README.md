# codsoft_taskno4

# Movie Recommendation System

This project implements a movie recommendation system using TF-IDF vectorization and cosine similarity. It also includes an evaluation function to measure the performance of the recommendation system using Mean Squared Error (MSE).

## Features

- **Content-Based Filtering**: Recommends movies based on their genre, director, and description.
- **TF-IDF Vectorization**: Converts movie descriptions into TF-IDF features.
- **Cosine Similarity**: Measures similarity between movies.
- **Performance Evaluation**: Evaluates the recommendation system using Mean Squared Error (MSE).

## Requirements

- `pandas`
- `scikit-learn`
- `scikit-surprise`
- `numpy`
- `nltk`

## Usage

- **Clone the repository**:
git clone https://github.com/Imaneamaaz/codsoft_taskno4.git
cd codsoft_taskno4.git
- **Example**:
To get top 5 movie recommendations for 'The Matrix':
```bash
print(get_recommendations('The Matrix'))

