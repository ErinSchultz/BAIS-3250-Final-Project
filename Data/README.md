Data folder contains our scraped data, or data from Kaggle, as well as our integrated data, all saved as CSV files.

## File Descriptions

imdb_53_raw_scrape.csv: the csv file created based on the data scraped from the IMDb website using 00_movies_scraped.ipynb.

MoviesOnStreamingPlatforms.csv: downloaded directly from the Kaggle database.
These files were then loaded into the 01_kaggle_imdb_merege.ipynb where all manipulation took place.

## Descripton of Data Sources
Our scraped data comes from IMDb's movie data base. The original data contained information on all movies released between January 1, 2000 and December 31, 2021. The entire site contained data on 89,781 movies over 360 pages. We scraped all movie data between January 1, 2019 and December 31, 2021. Our scraped dataset from IMDb contains 13,244 rows containing the title of the movie, the year it was released, and the IMDb rating.
https://www.imdb.com/search/title/?title_type=feature&release_date=2000-01-01,2021-12-31&countries=US&count=250&sort=release_date,desc 

Our datset from Kaggle includes data on 9,515 unique movies. There are 11 columns in the dataset but for our project we are only focused on the movie title, release year, Rotten Tomatoes score, and availability on each streaming platform. 
https://www.kaggle.com/datasets/sanyacodes/movies-dataset-netflix-prime-video-disney 

