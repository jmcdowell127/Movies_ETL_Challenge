# Movies ETL Challenge

## Overview 
After creating a movies and ratings dataset, Britta from Amazing Prime would like to keep it updated on a daily basis. To do so I have created an automated pipeline that does the following:
* Takes in new, recent movie data from Wikipedia, Kaggle, and MovieLens.
* Performs the appropriate transformations on the new data.
* Loads the data into already existing tables.

## Resources
* Software
  * Regular Expressions
  * Pandas
  * pgAdmin 4 version 5.2
  * PostgresSQL 13.4
  * Python 3.9.6
  * SQLAlchemy 1.4.19

## Results
The project was successful and a movies with ratings database was created. Below are images from this created dataset
* This is an image of the total amount of movies (6075) that are active in the database
  * <img width="214" alt="movies_query" src="https://user-images.githubusercontent.com/85372441/129393527-a5b86005-d257-4777-b490-5dc4df24181b.png">
* This is an image of the total amount of ratings for these 6075 movies. There are 26,024,286!
  * <img width="213" alt="ratings_query" src="https://user-images.githubusercontent.com/85372441/129393784-12020829-43f8-4d98-9377-9c9328635262.png">
* Here is a snip it of the first 10 movie ratings from the ratings table.
  * <img width="344" alt="ratings" src="https://user-images.githubusercontent.com/85372441/129394832-e1e4f7a4-d35f-49f9-b3b3-df038a5d2d70.png">
* By combining data from Wikipedia, Kaggle, and MovieLens and then removing any redundencies a complete database has been created with all pertinent information.

## Summary
This database will be very helpful for the Hackathon for Britta and Amazing Prime. In the future, I would suggest adding movie genres as a column in this database. I would also suggest pulling information from additional websites such as movierankings.net, they give more of a fan rating than a critics rating. Finally, I would suggest to include the movie titles in the ratings table so that a random user knows exactly which movie is being represented instead of having to reference the movieid. 

  
























