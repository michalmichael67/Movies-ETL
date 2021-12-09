# Movies-ETL

In this project, the goal was to perform the ETL process on movie data and add the data to a PostgreSQL database. The initial files were sourced from Wikipedia, Kaggle metadata, and MovieLens rating data. 

The three files were converted to a dataframe from either a CSV file or a JSON file. The three files were then merged and filtered to create a dataframe with movie data and ratings in one table.

Finally, the new dataframe was added as a csv to a SQL database.