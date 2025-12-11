# 🎬 Movie Recommendation System

A **React-based movie recommendation application** that allows users to discover trending movies, search for titles, and manage their own list of favorites—all through a modern, responsive UI.

---

## ✨ Features

* **🔎 Discover Movies:** Browse a list of *currently popular* movies fetched from the **TMDB API**.
* **🎥 Search Functionality:** Search for specific movies by title.
* **❤️ Favorites List:** Add or remove movies from your personalized favorites list.
* **📱 Responsive Design:** Clean, dark-themed UI optimized for all screen sizes.
* **⚡ Dynamic UI:** Interactive movie cards with smooth hover effects and instant favorite toggling.


## 🛠 Tech Stack

* **Frontend:** React, React Router, Vite
* **Styling:** CSS3
* **API:** The Movie Database (TMDB) API
* **State Management:** React Context API


## 📦 Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd <project-folder>
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

### 4. Build for production

```bash
npm run build
```


## 🚀 Usage

### **Home Page**

* View popular movies.
* Use the search bar to find specific titles.

### **Favorites Page**

* Access all your saved movies.

### **Add/Remove Favorites**

* Tap the **heart icon** on any movie card to toggle it in your favorites list.


## 📁 Project Structure

```
src/
├── pages/          # Main page components (Home.jsx, Favorites.jsx)
├── components/     # Reusable UI components (MovieCard.jsx, NavBar.jsx)
├── contexts/       # Context providers for state management (MovieContext.jsx)
├── services/       # API services (api.js)
└── css/            # Stylesheets for components and pages
```


## ⚠️ Important: API Key Expiration

The TMDB API key used in this project is for **demo purposes** and may expire.

To ensure continued functionality:

1. Register for a free account on **The Movie Database (TMDB)** website.
2. Generate your personal API key under your account settings.
3. Replace the demo key in `src/services/api.js`:

```js
const API_KEY = "YOUR_NEW_API_KEY_HERE";
```
