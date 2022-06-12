# Movies-ETL

Deliverable 1: Write an ETL Function to Read Three Data Files (25 points)
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.

Deliverable 2: Extract and Transform the Wikipedia Data (30 points)
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.

Deliverable 3: Extract and Transform the Kaggle Data (30 points)
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

Deliverable 4: Create the Movie Database (15 points)
Use your knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.

Upload the following to your Movies-ETL GitHub repository:

The ETL_function_test.ipynb file
The ETL_clean_wiki_movies.ipynb file
The ETL_clean_kaggle_data.ipynb file
The ETL_create_database.ipynb file
The Resources folder with the wikipedia_movies.json, movies_metadata.csv, movies_query.png, and ratings_query.png files.
A README.md that describes the purpose of the repository. Although there is no graded written analysis for this Challenge, it is encouraged and good practice to add a brief description of your project.
