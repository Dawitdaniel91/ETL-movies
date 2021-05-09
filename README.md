# ETL Movies
The process of extract , transform and loading is ETL. In this project we will create new data from the Wikipidia data,Kagle metadata and Movilen ratings data.Finaly transform and load the data into an existing PostgreSQL database.

In the analysis we create the following :
  . ETL function to read three data files;
  . extract and transform the Wikipidia data
  . extract and transform the kaggle and rating data
  . Load data into the PostgreSQL database.
 # Reduslts
 
 1. ETL function test
    Created three separate dataFrame wiki_movies_df, kaggle_metadata and ratings from Wikipedia JSON, the Kaggle metadata and MovieLens csv files.
 2. extract and transform the Wikipidia data
    We filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.
 3. extract and transform the kaggle and rating data
    Mix the data ,remove the duplicates , format and gruoped the data
 5. Load data into the PostgreSQL database.
    After cleaning and droping the unwanted data finally transfer the data into existing the PostgreSQl database.
    
   Table1.  Movies_query
   
   https://github.com/Dawitdaniel91/ETL-movies/blob/main/movies_query.png
   
   Table 2. Ratings_query
   
   https://github.com/Dawitdaniel91/ETL-movies/blob/main/ratings_query.png
   
   
   # Summery
    The ETL help the massive data different data by extract , transfer and load based on our needs.

 

