# Movie-Recommendation-System

![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/MovieImage.jpg)

# Dataset : **[The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)**
### About the Dataset :

**movies_metadata.csv** : Contains Informations like genres, release year, release date, budget, revenue etc. for 45000+ movies

**keywords.csv** : Contains keywords of reviews given by users for all movies in the movies_metadata.csv file

**credits.csv** : Contains Cast and Crew Information for all movies in the movies_metadata.csv file

**ratings_small.csv** : Contains 100 ratings from 700 users on 9,000 movies

**links_small.csv** : Contains IMDB and TMDB IDs of all movies featured in the ratings_small.csv file (About 9000 movies).

### Final Dataset Obtained After Data Cleaning, Data Wrangling and Merging credits.csv, links_small.csv, keywords.csv with movies_metadata.csv:
**MoviesData.csv** : Contains all information about 9081 movies.
The features of MoviesData.csv are as follows:
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/MovieDatainfo.png)

# Data Analysis :

## Genres Distribution in the Dataset :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Genres_Distribution.jpg)

## Distribution of production countries in the Dataset :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/PC_Distribution.jpg)

## Distribution of production house in the Dataset :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/PH_Distribution.jpg)

## Release Year Distribution :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Year_Distribution.jpg)

## Release Day Distribution :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Days_Distribution.jpg)

## Most frequently appearing actors/actresses in the dataset :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Actors_Distribution.jpg)

## Most frequently appearing directors in the dataset :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Directors_Distribution.jpg)

## Correlation Between The Columns budget, profit, revenue, runtime, vote_count, vote_average, rating_count, mean_rating and release_year :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Correlation_plot.jpg)

## Top 20 movies based on the popularity column in the dataset :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Movie_popularity.jpg)

## Top 20 movies based on the vote_count column in the dataset :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Movie_votecount.jpg)

## Top 20 movies based on the number of users rated in the dataset :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Movie_ratingcount.jpg)

## Top 20 high Budget Movies :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Movie_budget.jpg)

## Top 20 high Profit Movies :
![](https://github.com/disha2sinha/Movie-Recommendation-System/blob/master/Snapshots/Movie_profit.jpg)

# Popularity-Based Recommendation System :

