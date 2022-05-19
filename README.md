# Movie Recommendation system

This is a Movie Recommendation system using Alternating Least Squares (ALS) algorithm. 


## Description

The rapid growth of Internet and information increases the necessity of effective recommendation systems for filtering user preferred products. 
These systems track customer behavior, such as purchase history, browsing activity, share habits, ratings in order to model user preference. 
Here we introduce recommendation system model based on explicit feedback of user preferences of movies and visualize the recommendations. We use
ALS, which is one of the low rank matrix factorization algorithms for collaborative filtering. In collaborative filtering, users and items are presented as latent factors and ALS algorithm learns these latent factors by matrix factorization to make predictions.

## Dataset

The Dataset was taken from Kaggle.It contains metadata for all 45,000 movies listed in the Full MovieLens Dataset and 26 million ratings from over 270,000 users. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.


### Executing programs

* Data Analsis

Exploratory Data Analysis based on the Kaggle: The Movie Dataset to udnerstand the overall the number of ratings, users and movies, maximum number of movies that users provided, the distribution of rating, genres of rated movies and etc.

* Model    

ALS model generation, choosing the best hyperparameters with grid search, dividing the dataset to train,validation and test sets, testing the model and lastly recommending movies to users. 
After having recommended movies and favorite movies, scrapping IMDB website to show the movie posters. Movie posters are very important as they contain the message and feeling of the movie and help users to decide whether they want to watch the movie or not.

