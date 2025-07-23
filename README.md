 URL Shortener Frontend

This is a React-based frontend for a URL Shortener Statistics Page. It displays:
- List of shortened URLs
- Creation and expiry dates
- Click counts
- Detailed click data (timestamps, sources, location)

## Getting Started

### Prerequisites
- Node.js and npm installed

### Installation
1. Open a terminal in the `frontend` directory:
   ```
   cd d:/22_103/frontend
   npm install
   ```

### Running the App
1. Start the development server:
   ```
   npm run dev
   ```
2. Open the local URL shown in the terminal (usually `http://localhost:5173`) in your browser.

## Project Structure
```
frontend/
  ├── index.html
  ├── package.json
  ├── vite.config.js
  └── src/
      ├── App.jsx
      ├── main.jsx
      └── UrlStatsPage.jsx
```

## Customization
- Edit `src/UrlStatsPage.jsx` to change how statistics are displayed or to connect to a backend API.

## License
MIT
