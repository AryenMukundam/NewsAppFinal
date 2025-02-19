# News & Bookmarks App

A simple and modern news app that fetches the latest technology news and allows users to bookmark articles for later reading.

## Features
- Fetches real-time technology news using an API
- Bookmark articles for later reading
- Switch between "News" and "Bookmarks" tabs
- Responsive and animated UI
- Local storage support for bookmarks

## Technologies Used
- HTML
- CSS (with animations and responsiveness)
- JavaScript (for API fetching and local storage handling)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/news-bookmark-app.git
   ```
2. Navigate to the project folder:
   ```bash
   cd news-bookmark-app
   ```
3. Open `index.html` in your browser.

## API
This project uses the RapidAPI news API. Ensure you have a valid API key:
```javascript
const url = 'https://real-time-news-data.p.rapidapi.com/topic-news-by-section?...';
const options = {
  method: 'GET',
  headers: {
    'x-rapidapi-key': 'YOUR_API_KEY',
    'x-rapidapi-host': 'real-time-news-data.p.rapidapi.com'
  }
};
```
Replace `YOUR_API_KEY` with a valid API key from [RapidAPI](https://rapidapi.com/).

## Usage
1. Open the app.
2. View the latest technology news.
3. Click "Bookmark" to save an article.
4. Switch to the "Bookmarks" tab to see saved articles.
5. Remove bookmarks when no longer needed.
