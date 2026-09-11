# MovieHub — GitHub Pages Version

This is a **100% frontend** movie ticket booking project designed to work on GitHub Pages.

## Features
- Graphical MovieHub homepage
- 6 locally generated SVG movie posters
- Movie/showtime selection
- Interactive 60-seat layout
- Real booking persistence in browser `localStorage`
- Booking confirmation with unique code
- Ticket cancellation
- Responsive design
- No Flask, Python, SQLite or server required

## Deploy on GitHub Pages
Upload `index.html`, `style.css`, `script.js`, `images/`, and this README to a GitHub repository. In **Settings → Pages**, choose the branch containing these files and `/ (root)`. Your site will then be available at the GitHub Pages URL.

### Important
`localStorage` is browser-specific. It is suitable for a college/demo project, but it is **not a shared online database**. If you need all users to share bookings, use a hosted backend such as Supabase or Firebase.
