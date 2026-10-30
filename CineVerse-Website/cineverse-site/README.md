# CineVerse

A responsive movie-discovery website inspired by the original Judek Cinema layout, redesigned with a new name, fresh movie selection, and updated visual identity.

## Features
- Dark cinema-style interface with responsive mobile layout
- Trending titles from TMDb when connected
- Search for movies and TV shows
- Genre filters
- Movie/TV details, ratings, release dates and descriptions
- Persistent personal watchlist using browser local storage
- Sample titles and posters available before connecting TMDb

## Run locally
Open `index.html` in a browser. For best results, use a local static server (for example VS Code Live Server).

## Connect TMDb
Click **Connect TMDb** in the top bar and paste your TMDb Read Access Token. The token is stored in the browser's local storage on that device.

Get an API token at https://www.themoviedb.org/settings/api.

> This is a static front-end demo. A token entered in the browser is visible to that browser session and should be treated as a public client credential. For a production deployment, route TMDb requests through a server-side function and keep secrets in Vercel Environment Variables.

## Deploy to Vercel
1. Create a GitHub repository and upload `index.html` (and this README).
2. Import that repository into Vercel.
3. Use **Other** as the framework preset; set the build command and output directory to blank/default (the root contains `index.html`).
4. Deploy. Vercel will provide a unique public URL.
