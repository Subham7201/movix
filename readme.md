# Movix: A Movie Browsing App Built with React

Movix is a web application that allows users to browse, search, and view details of movies. The app is built using React and fetches movie data from The Movie Database (TMDb) API. It showcases popular movies, allows searching for specific movies, and displays detailed information about each movie.

## Features

- Browse popular movies
- Search for movies by title
- View detailed information about each movie
- Responsive design

## Technologies Used

- React
- React Router
- Axios
- TMDb API
- SCSS

## Installation and Setup

Follow these steps to get the project up and running on your local machine:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/movix.git
   cd movix
   ```

2. **Install the dependencies:**
   
   ```bash
   npm install
   ```
   
4. **Set up account on TMDB and generate API key and add in .env file:**
   
   ```bash
   REACT_APP_TMDB_API_KEY=your_api_key_here
   ```
   
6. **Start the development server:**
   
   ```bash
   npm run dev
   ```
   
   Go to the `http://localhost:5173`to see the app in action

## Usage

- **Browse Popular Movies:** The homepage displays a list of popular movies. Click on any movie to view its details.
- **Search for Movies:** Use the search bar at the top to find movies by their title. The search results will be displayed below the search bar.
- **View Movie Details:** Click on a movie from the list to view more details, including the synopsis, cast, and similar movies.   

You can see the project in action at [movix](https://movix-coral-phi.vercel.app/)
