## Project Objective:
The objective of this SQL project is to perform a detailed analysis of movies and TV shows
using the IMDb and TMDb scores, genres, actors, directors, release years, runtimes, and other
attributes. The analysis will focus on answering key questions related to content performance,
trends, and insights into the factors contributing to success.

## Datasets
**1. Title**

The titles dataset contains information about movies, TV shows, and other types of media
content. Each row corresponds to a unique movie or show and includes various attributes
related to the content.

## Columns in Titles Dataset:
● id: Unique identifier for each movie/show.

● title: The name of the movie or show.

● type: Type of the content (e.g., movie, show).

● release_year: Year the movie/show was released.

● runtime: Duration of the movie/show in minutes.

● genre: Genre(s) associated with the movie/show (e.g., Drama, Action, Comedy).

● production_country: Country in which the movie/show was produced.

● imdb_score: Rating given to the movie/show on IMDb.

● tmdb_popularity: Popularity score given to the movie/show on TMDb (The Movie Database).

● seasons: Number of seasons (only for TV shows).

● age_certification: Age rating for the content (e.g., PG, R).

● keyword: Keywords associated with the movie/show's content or themes.

**2. Credits**

The credits dataset contains information about the cast and crew of each movie or show. Each
row corresponds to a cast or crew member's contribution to a specific movie/show.
## Columns in Credits Dataset:
● title_id: Unique identifier that links to the id in the titles dataset.

● actor_name: Name of the actor or actress involved in the movie/show.

● director_name: Name of the director associated with the movie/show.

● role: Role of the person (e.g., actor, director, producer).

●character_name: The character name played by the actor (only for actors)

## Questions

*1. What were the top 10 movies according to IMDB score?*

*2. What were the top 10 shows according to IMDB score?*

*3. What were the bottom 10 movies according to IMDB score?*

*4. What were the bottom 10 shows according to IMDB score?*

*5. What were the average IMDB and TMDB scores for shows and movies?*

*6. Count of movies and shows in each decade*

*7. What were the average IMDB and TMDB scores for each production country?*

*8. What were the average IMDB and TMDB scores for each age certification for shows and movies?*

*9. What were the 5 most common age certifications for movies?*

*10. Who were the top 20 actors that appeared the most in movies/shows?*

*11. Who were the top 20 directors that directed the most movies/shows?*

*12. Calculating the average runtime of movies and TV shows separately*

*13. Finding the titles and directors of movies released on or after 2010*

*14. Which shows on Netflix have the most seasons?*

*15. Which genres had the most movies?*

*16. Which genres had the most shows?*

*17. Titles and Directors of movies with high IMDB scores (>7.5) and high TMDB popularity scores (>80)*

*18. What were the total number of titles for each year?*

*19. Actors who have starred in the most highly rated movies or shows*

*20. Which actors/actresses played the same character in multiple movies or TV shows?*


*21. What were the top 3 most common genres?*

*22. Average IMDB score for leading actors/actresses in movies or shows*

*23. Which movies or shows had the highest number of votes?*

*24. Which movies or shows had the longest runtime?*

*25. What were the top 5 most popular genres for movies?*

*26. How many movies or shows were released each year?*

*27. Which actors appeared in the most genres?*

*28. Which production countries have the highest number of movies or shows?*

*29. Which actors have the highest average rating across all their movies/shows?*

*30. Which shows had the most seasons?*

*31. Which movies had the highest box office revenue?*

*32. Which directors have worked on the most movies or shows?*

*33. What are the most common keywords or phrases in movie titles?*

*34. Which actors or actresses have the most frequent collaborations with the same director?*

*35. What were the most common movie ratings (IMDB scores) for movies released in a particular decade?*

*36. Which movies or shows had the highest popularity score on TMDB?*

*37. How many actors or actresses have starred in both movies and TV shows?*
