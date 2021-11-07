# Movies-ETL

# Summary
* The purpose of this repository project was to perform the extract, transform, and load process on the raw wiki and kaggle data, to use as clean data for an upcoming hack-a-thon. The cleaned data was then processed into the SQL database so the participants can gain easy access to the information.

# Included in the repository
* ETL_clean_kaggle_data.ipynb
* This jupyter notebook source file contains the ETL process used to transform the raw data from the kaggle source into useable data for the hack-a-thon.

* ETL_clean_wiki_movies.ipynb
* This jupyter notebook source file contains the ETL process used to transform the raw data from the wikipedia source into useable data for the hack-a-thon.

* ETL_create_database.ipynb
* This jupyter notebook source file includes the code needed for transferring the cleaned data into our SQL database.

* ETL_function_test.ipynb
* This jupyter notebook source file shows the function used to read in all three data sources, this is the extract process of ETL.

* Resources folder
* This folder contains the following files:
* movies_metadata.csv, wikipedia-movies.json, movies_query.PNG, and ratings_query.PNG.
* The movies_query.PNG and ratings_query.PNG show the final row count for our SQL data.