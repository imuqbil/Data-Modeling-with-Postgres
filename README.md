### Summary of the project

To create a star schema to be optimized for queries on song play analysis

#### - how to run the Python scripts
Run create_tables.py first, then run elt.py

#### - explanation of the files in the repository

test.ipynb shows the first few rows of each table.
create_tables.py drops and creates the tables. 
etl.ipynb reads and processes a single file from song_data and log_data and loads the data into the tables. 
etl.py reads and processes files from song_data and log_data and loads them into the created tables. sql_queries.py contains all sql queries, and is imported into the last three files above
