# Netflix Movie Data Analysis Project

![Netflix Logo](netflix.jpg)

## Overview
This project explores a dataset of Netflix movies to uncover key trends and insights that aid in understanding the platform's content landscape. The project uses Python for data manipulation and visualization to answer questions such as:
- What are the most frequent genres?
- Which movies have the highest and lowest popularity?
- Which year had the most movies released?

## Dataset
The dataset contains 9,827 entries with the following columns:
- **Release_Date**: The year the movie was released.
- **Title**: The name of the movie.
- **Overview**: A short description of the movie.
- **Popularity**: A metric indicating how popular the movie is.
- **Vote_Count**: The number of votes the movie received.
- **Vote_Average**: The average vote rating for the movie.
- **Original_Language**: The language in which the movie was originally released.
- **Genre**: A list of genres the movie falls into.
- **Poster_Url**: A link to the movie's poster.

## Features
- **Data Cleaning**:
  - Removed unnecessary columns such as `Overview` and `Poster_Url`.
  - Converted `Release_Date` to datetime format and extracted the year.
  - Split and exploded the `Genre` column for better analysis.
  - Categorized `Vote_Average` into `popular`, `average`, `below_avg`, and `not_popular`.

- **Data Exploration**:
  - Identified Drama as the most frequent genre.
  - Found that *Spider-Man: No Way Home* is the most popular movie.
  - Discovered that 2020 was the year with the most movie releases.

- **Visualization**:
  - Used Matplotlib and Seaborn to create visual representations of genre frequency, popularity, and voting trends.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/netflix-movie-analysis.git
