# Movies ETL
## Background and Deliverables
It was requested that an automated system be developed to assimilate new data from three different sources--Wikipedia data, Kaggle metadata, and MovieLens rating data--that would transform it, and then load the cleaned data into a PostgreSQL database.  The following deliverables were requested:
  - Write an ETL fuction to read the three data files
  - Extract and transform the Wikipedia data
  - Extract and transform the Kaggle data
  - Create a movie database 

## Resources
- Data Sources: movies_metadata.csv, ratings.csv, wikipedia-movies.json
- Software and Programming Languages: pgAdmin 4; PostgreSQL 11; Jupyter Notebook v. 6.4.6; Python v. 3.8.3 :: Anaconda, Inc.; conda v. 4.11.0

## Summary
A single function was written to harvest data from the three files, clean the Wikipedia and Kaggle data, merge the three data files and then load the data to PostgreSQL database.  The final product was a database of over 6000 movies that have been released since 1990. Information included, but was not limited to movie title, directors, producers, imdb id, budget, box office revenue, actors and actresses, etc.
