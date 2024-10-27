# Movie Recommendation System

## Project Overview

This project utilizes Natural Language Processing (NLP) techniques to build a movie recommendation system. The system takes a movie title as input and recommends five similar movies based on their genres, keywords, cast, and crew.

## Data Preprocessing

The project performs essential data preprocessing steps, including merging datasets, handling missing values, and transforming text data for analysis. Key steps involve converting string representations to usable formats and extracting relevant information from complex data structures.

## Feature Extraction

The project employs the following feature extraction techniques:

- **CountVectorizer**: Converts the text data into numerical features using the bag-of-words approach.
- **Porter Stemmer**: Reduces words to their base form to minimize dimensionality.

## Recommendation Algorithm

The project utilizes a straightforward recommendation algorithm that calculates the similarity between movies based on their features. The algorithm takes a movie title as input and returns the top five similar movies.

## Code Organization

The code is structured into the following sections:

1. Data loading and preprocessing
2. Feature extraction
3. Recommendation algorithm
4. Example use case

## Dependencies

The project requires the following dependencies:

- `numpy`: A fundamental package for numerical computing in Python, used for handling arrays and performing mathematical operations.
- `pandas`: A powerful data manipulation library that provides data structures like DataFrames for cleaning and analyzing datasets.
- `ast`: A module that helps in parsing and evaluating Python expressions, useful for handling complex data formats.
- `nltk`: The Natural Language Toolkit, which provides tools for working with human language data, essential for NLP tasks.
- `sklearn`: A comprehensive machine learning library that offers tools for building and evaluating machine learning models.


## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Indrajit1465/Movie-Recommender-System.git
