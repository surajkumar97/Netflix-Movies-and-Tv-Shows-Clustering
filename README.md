# Netflix-Movies-and-Tv-Shows-Clustering
## Project Summary -
The Netflix Movies and TV Shows Clustering project aims to cluster similar movies and tv shows available on Netflix into different clusters based on their content. The project begins with dataccollected from the third-party Netflix search engine, which contains information about more than 7,000 movies and TV shows available on the platform.

The data set contained details about movies and TV shows available on Netflix. Descriptive statistics were computed for each variable as part of the analysis, and visualizations were made to investigate the relationships between the various variables. We created a number of graphs, such as the scatterplot, distplot, count plot, bar plot, pair plot, heatmap, pie plot, and box plot to gain insight from the dataset. The dataset containing 12 columns and 7787 rows. This dataset contains no values that are duplicates. The some values for the director, cast, country, date added, and rating are null. Everything else is categorical, with the exception of the numerical feature release year. Although the datatype of the date_added feature's dates incorrectly associates an object, it contains dates.
## Problem Statement
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.
### In this project, you are required to do,
Exploratory Data Analysis

Understanding what type content is available in different countries

Is Netflix has increasingly focusing on TV rather than movies in recent years.

Clustering similar content by matching text-based features
## Attribute Information
show_id : Unique ID for every Movie / Tv Show

type : Identifier - A Movie or TV Show

title : Title of the Movie / Tv Show

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Releaseyear of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Genere

description: The Summary description

## Conclusions:

1. It was interesting to find that majority of the content available on Netflix is Movies.

2. But in the recent years it has been focusing more on Tv-Shows.

3. Most of these contents are released either in the year ending or the beginning.

4. United States and India are among the top 5 countries that produce all of the available content on the platform.

5. Also 6 of the actors among the top ten actors with maximum content are from India.

6. TV-MA tops the charts, indicating that mature content is more popular on Netflix.

7. k=10 was found to be an optimal value for clusters using which we grouped our data into 10 distinct clusters.

8. Using the given data a simple recommender system was created using cosine_similarity and recommendations for Movies and Tv Shows were obtained.

## Future Scope:

1. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

2. More time could be given into building a better recommender system, which later can be deployed on web for usage.
