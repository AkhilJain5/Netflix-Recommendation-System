# Netflix Movie Recommender System

This is a simple web application that provides movie recommendations based on user input. The recommendations can be either by movie title or by genre.

## Installation

First, clone the repository:

```bash
git clone https://github.com/your_username/netflix_movie_recommender.git
cd netflix_movie_recommender

```


Then, install the required packages using pip:

```bash
pip install -r requirements.txt

```

## Usage

1. Run the jupyter NB:

   ```bash

   Movie_recommendations.pynb
     ```


2. Open your web browser and go to [http://localhost:5000](http://localhost:5000).

3. Enter either the name of a movie or a genre to get recommendations.

## Features

- **Recommendations by Name:** Enter the name of a movie to get recommendations of similar movies.
- **Recommendations by Genre:** Enter a genre to get recommendations of top-rated movies in that genre.
- **Data Visualization:** The application includes visualizations of the distribution of movie ratings and the top 10 movie genres.

## Data

The movie data is sourced from a CSV file named `netflix_titles.csv`. It includes information about movie titles, directors, cast, genre, description, and ratings.

## Technologies Used

- Python
- Flask
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Contributing

Contributions are welcome! If you'd like to add new features, fix bugs, or improve the documentation, feel free to open a pull request.





