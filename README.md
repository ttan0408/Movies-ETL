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
      
      
      
    2 Extract and Transform the Wikipedia Data
    3 Extract and Transform the Kaggle data
    4 Create the Movie Database
