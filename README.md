# Recommendation_System_movies
PROJECT OVERVIEW

Jaba Movie Shop endeavors to optimize user engagement and satisfaction through the implementation of a recommendation system. Jaba Movie Shop seeks to leverage on the extensive database of movieLens, to ensure that clients are paired with films that resonate with their preferences. The movies with high ratings are likely to be the mostly watched movies indicating customer satisfaction.


Objective
The objective of this project is build a model that provides the top movie recommendations to a user, based on their ratings of other movies. By leveraging machine learning algorithms, collaborative filtering and content-based filtering the project aims to:

Enhance user engagement by providing a platform where they get best recommendations based on their reviews, tags and ratings.
Build a model that provides the top movie recommendations to a user.
Enhance customer satisfaction.



Business Problem
Jaba Movie Shop aims at optimizing user engagement and satisfaction through the implementation of a recommendation system leveraging the MovieLens dataset. The Movie Shop acknowledges the importance of understanding consumer preferences and viewing behaviors in the competitive entertainment landscape. By analyzing user ratings and preferences, it seeks to enhance content recommendations. Fostering a stronger client loyalty and solidifying its position as an entertainment provider.


Data Understanding
The dataset used in this project was obtained from rom the GroupLens research lab at the University of Minnesota, which contains 100,000 user ratings. This makes it highly suitable for addressing the business problem at hand of developing a recommendation system. Contained in the dataset are:

User Id and Movie Id - are unique identifiers that are consistent within the movieLen datasets.
Timestamp - represent seconds since midnight Coordinated Universal Time (UTC) of January 1,1970.
Rating - movie ratings by the different users made on a 5-star scale, with half-star increments.
Tag - user generated metadata about different movies.
Genre - is a pipe-separated list of different type of movies.
tmdbId and imdbId - are unique identifier for movies.
title - movie titles that are entered manually or imported from https://www.themoviedb.org/

The libraries required;

```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import warnings
warnings.filterwarnings("ignore")
```
DATA EXPLORATION






