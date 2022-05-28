# Movies-ETL

## Project Overview

- This project is a Hackathon for Amazing Prime Movies.

- In this project, we are learning ETL process, which means extract, transform and load. Extract raw data from original resources, then clean and transform them to readable and useful data. After that, we load these cleaned data to the database for further analysis or and review.

- In this project, we downloaded three raw data files from Wikipedia, Kaggle and Movielens. The wiki and Kaggle data had a lot over overlap, so we cleaned them by filtering and dropping duplicated/useless rows, transferring column values to readable ones, and merging two tables into a comprehensive one. We also created nested functions to organize our cleaning/transforming process for huge data file such as "ratings.csv" for movie ratings. Finally, we loaded our cleaned movie data and the raw rating file to pgAdmin, a SQL database, for further analysis.

- The project ended here for now, but there were tons of new concepts to review and digest for future usage.
