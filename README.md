Movie Recommendation System
A React-based movie recommendation application that allows users to discover popular movies, search for specific titles, and manage a personalized list of favorites.

Features
Discover Movies: Browse a list of currently popular movies fetched from the TMDB API.
Search Functionality: Search for specific movies by title.
Favorites List: Save your favorite movies to a dedicated list for easy access.
Responsive Design: Optimized for various screen sizes with a clean, dark-themed interface.
Dynamic UI: Interactive movie cards with hover effects and instant favorite toggling.

Tech Stack
Frontend: React, React Router, Vite
Styling: CSS3
API: The Movie Database (TMDB) API
State Management: React Context API

Installation
Clone the repository:

Bash
git clone <repository-url>
cd <repository-directory>
Install dependencies:

Bash
npm install
Start the development server:

Bash
npm run dev
Build for production:

Bash
npm run build

Usage
Home Page: View popular movies or use the search bar to find specific titles.
Favorites Page: Access your saved movies.
Add/Remove Favorites: Click the heart icon on any movie card to add or remove it from your favorites list.

Project Structure
src/pages: Contains main page components (Home.jsx, Favorites.jsx).
src/components: Reusable UI components (MovieCard.jsx, NavBar.jsx).
src/contexts: Context providers for state management (MovieContext.jsx).
src/services: API service functions (api.js).
src/css: Stylesheets for components and pages.

Important Note: API Key Expiration
The API key currently used in this project is for demonstration purposes and may expire or be revoked in the future. To ensure the app continues to function correctly:
Register for a free account at The Movie Database (TMDB).
Generate your own API key from your account settings.

Open src/services/api.js and replace the API_KEY constant with your new key:
const API_KEY = "YOUR_NEW_API_KEY_HERE";
