# group-assingment-1
The first part of our group assignment. 
Our web application will be a Christmas movie database including four tables (movie, director, actor and studio). 

The movie table consists of seven fields which are: movie_ID (PK), director_id (FK), movie_year, movie_name, rating (ex: G, PG, PG-13, etc.) , actor_ID (FK), and genre

The director table consists of four fields, including: director_id (PK), first_name, last_name and dob, studio_id (FK)

The actor table consists of: actor_id (PK) , first_name, last_name, and dob.
NOTE: for simplicity, we are assuming that the actor table will only include the main actor for each movie. 

The studio table connects with the Director table to describe which director works for which studio and it consists of: studio_id (PK), studio_name, year_founded, and ceo

The relationships amongst the tables for the database are the following: 
  A Movie is directed by one and only one director, but a director can direct one-to-many movies. 
  An Actor can star in one to many movies, while a movie has one and only one lead actor.
  A director works for one and only one studio, where as a studio employees one-to-many directors. 


