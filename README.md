# Movie_Recommender_System

# Aim
The Aim of my project is to build a recommendation system that will recommend you movies based on content similarity.

# Project Discription
To build this project at first I gatthered dataset that will contain all the details about the movie. After importing my dataset I filter out the noice and created a new dataset with all the required tags for content based recommendation. After creating new dataset My main task is to find out similarity between each movies, for that I first converted all my tags intially in string to a vector using CountVectorize module in sklearn.feature_extraction.text library. Once i got each movie tags as a vector I imported Cosine_Similarity from sklearn.metrics.pairwise module and sorted five most similar movies in decendeing order. After this I used Streamlit to run my web app. I also fetched posters for my recommended movies from tmdb API.

# API used
https://developers.themoviedb.org/3/movies/get-movie-details

# Technologies Used
Python
Streamlit
Sklearn

# System Flow Diagram
![my4](https://user-images.githubusercontent.com/80889801/170462931-9dbc99de-8590-42cb-90d8-db22441a548b.png)

# The WebApp
![webapp1](https://user-images.githubusercontent.com/80889801/170466575-8bae6d92-34aa-4641-86bd-2fdd0ddb3325.png)

![webapp2](https://user-images.githubusercontent.com/80889801/170466692-01995d00-c042-48c0-90c8-53f8f39b97d6.png)

# Developer

Prashant Agrawal
