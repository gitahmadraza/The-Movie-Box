# The Movie Box

Welcome to **The Movie Box**, your fun and interactive movie recommendation site — live now via GitHub Pages:  
https://gitahmadraza.github.io/The-Movie-Box/

---

## Overview

**The Movie Box** is a multi-page, front-end web app built using **HTML, CSS, and JavaScript**, powered by **The Movie Database (TMDb) API**. It helps users discover new movies through a playful Wheel of Fortune-style interface and browse top-rated titles.

---

## Features

- **Homepage**  
  Introduces the app and directs users to explore or spin for suggestions.

- **Movie Wheel Page**  
  Select a genre (and optionally mood in development), then spin to receive a random movie recommendation complete with poster, title, overview, rating, and release year.

- **Top Rated Movies Page**  
  Browse a grid of globally top-rated films fetched from TMDb, with posters, titles, and ratings.

---

## Tech Stack

- **Frontend:** Vanilla HTML, CSS, and JavaScript  
- **API Integration:** TMDb API (image and metadata) for dynamic content  
- **Hosting:** GitHub Pages for live deployment

---

## File Structure

/
├── index.html
├── wheel.html
├── top-rated.html
├── css/
│ └── style.css
└── js/
├── main.js
├── wheel.js
└── top-rated.js

yaml
Copy
Edit

- `main.js`: General utilities and TMDb helper functions  
- `wheel.js`: Handles movie wheel logic (fetching & spinning)  
- `top-rated.js`: Loads top-rated movies in a grid

---

## How It Works

1. **Movie Wheel Page**  
   - User chooses a genre, clicks **Spin**  
   - The app fetches a pool of movies from TMDb using `/discover/movie`  
   - Adds a fun rotation animation  
   - Selects and displays one random movie’s details

2. **Top Rated Page**  
   - Fetches the top-rated movies from TMDb using `/movie/top_rated`  
   - Renders a responsive movie grid with images and ratings

---

## Usage Tips

- Currently, the **TMDb v3 API key** is placed directly in the JS for development and private testing.
- **Reminder**: Before going public or open-source, move the API key behind a backend proxy or use environment variables to secure it.

---

## Credits

Powered by **The Movie Database (TMDb)** — thank you for your rich movie database!  
Made with ❤️ by **Ahmad Raza**

---

## License

Feel free to modify, adapt, or build upon this project. Consider adding a LICENSE file to specify terms if sharing publicly.
