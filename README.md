# FlareHabit Landing Page

Official website for FlareHabit — a clean, gamified habit tracker with XP, levels, achievements, streaks, and AI-powered habit suggestions. This repo hosts the static landing page deployed via Netlify, showcasing app features, screenshots, and links to download, support, and legal pages.

## Local Development

### Quick Start (Open in Browser)
Simply open `index.html` in your web browser. However, for the best experience (especially for testing forms), use a local server.

### Using Python HTTP Server
If you have Python installed:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then open `http://localhost:8000` in your browser.

### Using Node.js http-server
If you have Node.js installed:
```bash
# Install globally (one time)
npm install -g http-server

# Run in project directory
http-server
```
Then open the URL shown (typically `http://localhost:8080`).

### Using VS Code Live Server
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Project Structure
```
flarehabit-landing/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── terms.html          # Terms of service page
├── assets/
│   └── css/
│       └── styles.css  # Main stylesheet
└── README.md           # This file
```

## Features
- Modern, responsive design
- Hero section with app preview
- Feature highlights
- AI Suggestions showcase
- Gamification section
- Dashboard preview
- Screenshot gallery
- Email signup (Netlify Forms compatible)
- Social meta tags

## Deployment
This site is designed to be deployed on Netlify. Simply drag and drop the project folder or connect your Git repository.
