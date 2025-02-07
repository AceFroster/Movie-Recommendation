# Movie Recommendation System
A simple movie recommendation system that suggests similar movies based on their descriptions. Built using Python, TF-IDF for text processing, and cosine similarity for finding similarities between movies.

## Description
This project is a movie recommendation system that helps users discover movies based on their preferences. The idea is simple: given a movie title, the system will find and recommend similar movies based on their descriptions or overviews.

The process begins with a movie dataset that includes details like movie titles, descriptions, release dates, and more. The system then cleans the data, handles any missing or duplicate values, and processes the movie descriptions into a format that the machine can work with.

Using TF-IDF (Term Frequency-Inverse Document Frequency), the descriptions are transformed into numerical vectors that capture the importance of each word in a movie’s overview. Then, cosine similarity is used to compare these vectors, measuring how similar the movies are to one another. This allows the system to recommend the 10 most similar movies for any given movie title.

While the approach is simple, it can be quite effective for discovering new films that match your tastes. So, if you’ve ever finished watching a movie and wondered, “What else is like this?”, this system is designed to answer that question.

## Key Features
Data Cleaning: Handles missing values and duplicates, ensuring a clean and usable dataset.

Text Processing: Uses TF-IDF to transform movie descriptions into numerical data that can be compared.

Cosine Similarity: Measures the similarity between movies based on their descriptions, offering relevant suggestions.

Recommendation Engine: Takes a movie title and returns 10 similar films based on the movie descriptions.


## Requirements
Python 

Pandas

NumPy

Scikit-learn

You can install the required libraries using pip:

``` bash
pip install pandas numpy scikit-learn
```


## Example
If you input the title "Inception", the system will analyze its description and recommend movies with similar themes or plots. Some possible recommendations might include:

   The Wrong Missy
   
   Central Intelligence
   
   A History of Violence
   
...because, apparently, all movies with mind-bending plots are related.

While the recommendations aren’t perfect, the system does a pretty solid job of suggesting movies you might enjoy based on the ones you've already watched.
