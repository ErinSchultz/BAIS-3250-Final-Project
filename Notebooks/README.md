Notebooks file contains all Python notebooks with code. These include:

- Web Scraping (00_movies_scraped.ipynb)
- Data integration and cleaning (01_kaggle_imdb_merge.ipynb)
- Descriptive analysis (our questions with results)

## 00_movies_scraped.ipyn

Scraping the IMDb website (https://www.imdb.com/search/title/?title_type=feature&release_date=2000-01-01,2021-12-31&countries=US&count=250&sort=release_date,desc) for the title, release year, and IMDb rating for these movie.
This is where we ran into one of the limitations of the project, that being our original plan was to scrape around 89,418 movies released between January 1, 2000, to December 31, 2021. However, due to a time limit and computer capacity, we had to forcefully stop the scraping after ~45 hours, or 53/358 completed loops. This left us with 13,244 movies before dropping any null values.

## O1_kaggle_imdb_merge.ipynb

Kaggle data import, scraped IMDb data import, merging of these two dataframes, and answering business questions with visualizations.
Once the scraped data from the IMDb website was merged with the data from the Kaggle dataset, we were left with 483 movies that were available on one of the four streaming platforms and had an IMDb rating available.
