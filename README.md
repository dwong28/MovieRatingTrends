# MovieRatingTrends

This project was created to examine the trends of movie ratings through different years to see if various societal changes had an effect on moviemaking and whether movies in general were becoming more violent and unsuitable for children, or if the industry as a whole was moving towards more child friendly films. 

The data is sourced from GroupLens, and is linked here: http://grouplens.org/datasets/movielens/

# movie.csv
This file contains information about each movie, such as:
   - movie id
   - Title of Movie
   - Genre(s) of Movie
   
# link.csv
This file serves as the middle ground, and connects each unique movieID to its corresponding IMDB page on the Internet. It's from there that the movie rating (G, PG, PG-13, R, NC-17) was sourced. 

Note: The project is currently set to run across 3 years. While a longer range can be run, it is not recommended as the sheer volume of the data set results in a very long wait time. 
