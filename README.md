# Movie-Recommendation-System
 A Movie Recommendation System based on The Movies Dataset.
 <br />I implemented the recommendation algorithms for Collaborative Filtering, Content Based Filtering and Demographic Filtering, and ensemble these model to build a final recommender. 
 <br />
 Three types of basic recommendation system:
 <br />
 <br />Demographic Filtering: This is a generalized recommendations for every user based on movie popularity and/or genre. The System recommends the same movies to users with similar demographic features.
 <br />Content Based Filtering: An engine that computes similarity between movies based on certain metrics and suggests movies that are most similar to a particular movie that a user liked.
 <br />Collaborative Filtering: This system matches persons with similar interests and provides recommendations based on this matching.

## Context
<br />These files contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.
<br />This dataset also has files containing 100,000 ratings from 700 users for a small subset of 9,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.

## Content
This dataset consists of the following files:
<br />movies_metadata.csv: The main Movies Metadata file. Contains information on 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies.
<br />
<br />keywords.csv: Contains the movie plot keywords for our MovieLens movies. Available in the form of a stringified JSON Object.
<br />
<br />credits.csv: Consists of Cast and Crew Information for all our movies. Available in the form of a stringified JSON Object.
<br />
<br />links.csv: The file that contains the TMDB and IMDB IDs of all the movies featured in the Full MovieLens dataset.
<br />
<br />links_small.csv: Contains the TMDB and IMDB IDs of a small subset of 9,000 movies of the Full Dataset.
<br />
<br />ratings_small.csv: The subset of 100,000 ratings from 700 users on 9,000 movies.

The Full MovieLens Dataset consisting of 26 million ratings and 750,000 tag applications from 270,000 users on all the 45,000 movies.

This dataset is an ensemble of data collected from TMDB and GroupLens.
<br />The Movie Details, Credits and Keywords have been collected from the TMDB Open API. This product uses the TMDb API but is not endorsed or certified by TMDb. Their API also provides access to data on many additional movies, actors and actresses, crew members, and TV shows.
The Movie Links and Ratings have been obtained from the Official GroupLens website.
