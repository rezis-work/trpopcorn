live link - https://trpopcorn.netlify.app/

TRPopcorn - Movie Tracker
Overview
TRPopcorn is a simple React-based movie tracking app that allows users to search for movies, view details about them, and track movies they have watched. Users can add movies to their watched list, rate them, and see a summary of their watched movies. The app uses the OMDB API to fetch movie data.

Features
Search Movies: Users can search for movies using the search bar. The app fetches movie data from the OMDB API based on the user's input.

Movie Details: Clicking on a movie in the search results displays detailed information about the selected movie, including the poster, title, release year, genre, IMDb rating, plot, starring actors, and director.

Add to Watched List: Users can add movies to their watched list, providing their own rating. The app tracks IMDb ratings, user ratings, and runtimes for each watched movie.

Delete from Watched List: Users can remove movies from their watched list if they no longer want to track them.

Watched Movies Summary: The app provides a summary of the movies users have watched, including the number of movies, average IMDb rating, average user rating, and average runtime.

How to Run the App
Clone the repository to your local machine.

bash
Copy code
git clone https://github.com/rezis-work/trpopcorn.git
Navigate to the project directory.

bash
Copy code
cd trpopcorn
Install dependencies.

bash
Copy code
npm install
Obtain an API key from OMDB API and replace the placeholder KEY in App.jsx with your actual API key.

javascript
Copy code
const KEY = "your_actual_api_key";
Start the development server.

bash
Copy code
npm start
Open your browser and visit http://localhost:3000 to use the app.

Credits
TRPopcorn is created by Rezi Karanadze.

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
