# Movies-ETL

 ## Background 
    Our team need to work with Britta to create an an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Data  are available from three different sources : Wikipedia data, Kaggle metadata, and the MovieLens rating data. The challlegen of this task is we need to one function that take all threes and performs the ETL process by adding the data to a PostgreSQL database. We plan the task into 4 different steps : 
    
    1 Write an ETL Function to Read Three Data Files
      By define the extract_transform_load function we were able to converts the Wikipedia JSON file to a Pandas DataFrame. The dataframe is displayed for JSON file as shown         below :
      
      https://github.com/ttan0408/Movies-ETL/blob/main/dataframe_display_JSON.PNG
      
      The Kaggle metadata file was able to convert to a Pandas DataFrame, and the DataFrame is displayed  below :
      
      https://github.com/ttan0408/Movies-ETL/blob/main/Kaggle_metadata_file.PNG
      
      The MovieLens ratings data file was able to convert to a Pandas DataFrame, and the DataFrame is displayed :
      
      https://github.com/ttan0408/Movies-ETL/blob/main/The_MovieLens_ratings_data_file.PNG
      
      All the code is located at : 
      
      https://github.com/ttan0408/Movies-ETL/blob/main/ETL_function_test.ipynb
      
    2 Extract and Transform the Wikipedia Data
    
      After finished creating fucntion that allow to read three data files, we do the refactoring to the code. Using our knowledge of Python, Pandas, the ETL process, and           code refactoring, extract and transform the Wikipedia data so we can merge it with the Kaggle metadata.
      
      After refactoring, cleaning data for box office, budget, release date, and running time we create movie_df and displayed it as below :
      
      Movie_df
      https://github.com/ttan0408/Movies-ETL/blob/main/Movie_DF.PNG
      
      Movie_df columns checking 
      https://github.com/ttan0408/Movies-ETL/blob/main/Movie_DF_Column.PNG
      
      And the ETL_clean_wiki_movie jupyter code is shown below :
      https://github.com/ttan0408/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb
      
    
    3 Extract and Transform the Kaggle data
      We have done ETL for JSON wiki movie data, now we have to do similar steps for Kaggle data and merge them toghether with movie_df. After finished the code and run here       are the results for wiki_movie_df, movies_with_ratings_df, and movies_df
      
      wiki_movie_df
      
      https://github.com/ttan0408/Movies-ETL/blob/main/wiki_movies_df.PNG
      
      movies_with_ratings_df
      
      https://github.com/ttan0408/Movies-ETL/blob/main/movies_with_ratings_df.PNG
      
      
      movies_df
      
      https://github.com/ttan0408/Movies-ETL/blob/main/wiki_movies_df.PNG
      
    
    4 Create the Movie Database
