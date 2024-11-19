# Movie_rec
# Movie Recommendation System

This project is a **Movie Recommendation System** designed to recommend movies based on user preferences. It is built using the **Content-Based Filtering** approach, leveraging **Cosine Similarity** to compute the similarity between movies based on their features, such as genres, cast, director, and descriptions.

## Project Overview

The goal of this project is to provide personalized movie recommendations by analyzing the features of the movies in a dataset. Users can input a movie title, and the system will suggest a list of movies that are most similar to the selected one. This system is ideal for helping users discover movies they are likely to enjoy based on their tastes.

## Features

- **Content-Based Filtering**: The system analyzes the features of the movies to recommend similar ones.
- **Cosine Similarity**: Measures the similarity between feature vectors to identify related movies.
- **Interactive User Interface**: Built using **Streamlit**, providing a simple and user-friendly way to interact with the system.
- **Scalable Design**: The system can easily be extended with additional features or integrated into larger applications.

## Dataset

The project uses a movie dataset that includes the following information:
- **Movie Titles**: Names of the movies.
- **Genres**: Categories or types of the movies.
- **Cast and Crew**: Key personnel involved in the movie.
- **Descriptions**: Brief overviews or summaries of the movies.

It is important to preprocess the dataset to handle missing values, standardize text, and create a suitable format for feature extraction.

## How It Works

1. **Feature Extraction**:
   - The system extracts key attributes like genres, cast, crew, and descriptions.
   - These attributes are combined to form a feature vector for each movie.

2. **Cosine Similarity Calculation**:
   - Cosine Similarity is used to measure how similar one movie's features are to another.
   - Movies with higher similarity scores are considered more relevant.

3. **Recommendation**:
   - When a user inputs a movie title, the system finds the most similar movies based on their feature vectors.

## Requirements

To run this project, you need the following dependencies:

- Python 3.x
- pandas
- numpy
- scikit-learn
- Streamlit

Install these libraries using the following command:

```bash
pip install -r requirements.txt
