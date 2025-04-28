# Movie Finder App

This is a movie discovery app built with **React**. The app allows users to search for movies, view trending movies, and explore popular movies. It fetches movie data from the [TMDB API](https://www.themoviedb.org/documentation/api) and displays it with detailed information like movie posters, titles, and more.

## Features

- **Search Movies**: Users can search for movies by title.
- **Trending Movies**: Displays a list of currently trending movies.
- **Movie Details**: View movie posters and other details for all fetched movies.
- **Responsive Design**: Works well on both desktop and mobile devices.

## Tech Stack

- **React**: For building the UI.
- **TMDB API**: To fetch movie data.
- **Appwrite**: Used to track search counts for movies
- **React-Use**: For debouncing the search term input.
- **CSS**: For styling the components.

## Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/movie-finder-app.git
    cd movie-finder-app
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**:
    - Create a `.env` file in the root of the project and add your TMDB API key:
      ```env
      VITE_TMDB_API_KEY=your_tmdb_api_key
      ```

4. **Run the app**:
    ```bash
    npm run dev
    ```
