Assets folder contains additional information to help users understand the context of the data.

## Data Dictionary

### A list of each feature, its data type, which of our two sources the feature came from, and then a brief description of what the feature is.

| Field           | Type        | Source | Description                                                                                                         |
| --------------- | ----------- | ------ | ------------------------------------------------------------------------------------------------------------------- |
| ID              | Numeric     | Kaggle | Unique identifier for each movie                                                                                    |
| Title           | Text        | Both   | Full title of the movie as it appears on the streaming platforms                                                    |
| Year            | Date        | Both   | Release year of the movie, when the movie was first made available to the public                                    |
| Rotten Tomatoes | Numeric     | Kaggle | The movie’s score on Rotten Tomatoes on a scale of 0 to 100                                                         |
| Netflix         | Categorical | Kaggle | A binary indicator (0 or 1) of whether the movie is available on Netflix, with 1 indicating availability            |
| Hulu            | Categorical | Kaggle | A binary indicator (0 or 1) of whether the movie is available on Hulu, with 1 indicating availability               |
| Prime Video     | Categorical | Kaggle | A binary indicator (0 or 1) of whether the movie is available on Amazon Prime Video, with 1 indicating availability |
| Disney+         | Categorical | Kaggle | A binary indicator (0 or 1) of whether the movie is available on Disney+, with 1 indicating availability            |
| IMDb Rating     | Numeric     | IMDb   | The movie’s average rating on IMDb on a scale of 0.0 to 10.0                                                        |
