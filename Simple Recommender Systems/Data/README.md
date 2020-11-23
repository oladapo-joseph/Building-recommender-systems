# Dataset 

About the Dataset
The dataset files contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. This dataset captures feature points like cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts, and vote averages.

These feature points could be potentially used to train your machine learning models for content and collaborative filtering.

This dataset consists of the following files:

*movies_metadata.csv*: This file contains information on ~45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, genre, revenue, release dates, languages, production countries, and companies.
*keywords.csv*: Contains the movie plot keywords for our MovieLens movies. Available in the form of a stringified JSON Object.
credits.csv: Consists of Cast and Crew Information for all the movies. Available in the form of a stringified JSON Object.
*links.csv*: This file contains the TMDB and IMDB IDs of all the movies featured in the Full MovieLens dataset.
*links_small.csv*: Contains the TMDB and IMDB IDs of a small subset of 9,000 movies of the Full Dataset.
*ratings_small.csv*: The subset of 100,000 ratings from 700 users on 9,000 movies.
The Full MovieLens Dataset comprises of 26 million ratings and 750,000 tag applications, from 270,000 users on all the 45,000 movies in this dataset. It can be accessed from the official GroupLens website.

Note: The subset dataset used in today's tutorial can be downloaded from [here](https://www.kaggle.com/rounakbanik/the-movies-dataset/data).