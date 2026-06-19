Movie Recommendation App

A mobile application built with React Native and Expo that allows users to discover movies, browse ratings, and get movie recommendations using IMDb-style movie data.

Features-

Search for movies by title
View movie details
Display movie ratings and information
Browse recommended movies
Responsive mobile-friendly UI
Fast API integration using Axios
Cross-platform support (Android, iOS, and Web)

Tech Stack-

React Native
Expo
JavaScript (ES6+)
Axios
React Native Elements
Responsive Font Size
Safe Area Context

Dependencies-

{
  "axios": "^0.27.2",
  "expo": "~46.0.9",
  "react": "18.0.0",
  "react-native": "0.69.5",
  "react-native-elements": "^1.2.7"
}

Installation-

Clone the repository
*git clone https://github.com/yourusername/movie-recommendation-app.git
*cd movie-recommendation-app
*Install dependencies
    npm install
*Start the application
    npm start
*Run on Android
    npm run android
*Run on iOS
    npm run ios
*Run on Web
    npm run web
📂 Project Structure
movies_imdb/
│
├── assets/
├── components/
├── screens/
├── services/
├── App.js
├── package.json
└── README.md
How It Works
User searches for a movie.
The application sends requests to the movie API using Axios.
Movie details, ratings, and recommendations are fetched.
Results are displayed in an intuitive mobile interface.


This project helped me gain practical experience in:

React Native development
Mobile UI design
API integration
State management
Responsive application development
Expo ecosystem

Future Improvements-

User authentication
Favorites/Watchlist feature
Dark mode support
Advanced filtering and sorting
Personalized recommendations
Offline caching
