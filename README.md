# Keeper App

A minimalist note-taking application built with React, allowing users to create, view, and manage notes with a clean, intuitive interface.

## Description

Keeper App is a lightweight note-taking application inspired by Google Keep. It provides a simple yet elegant way to capture and organize your thoughts and ideas. The app features a responsive design with smooth animations and an organized component structure.

## Features

- **Create Notes:** Add new notes with a title and content through an intuitive form
- **Display Notes:** View all saved notes in a card-based layout with smooth hover animations
- **Responsive Navigation Bar:** Includes a search field and action buttons (refresh, list view, settings, user profile)
- **Header Section:** Branded header with animated entrance effect
- **Footer:** Dynamic footer displaying current copyright year
- **Styled Components:** Professional styling with gradient backgrounds, shadows, and transitions

## Installation / Setup

1. Clone the repository:
```bash
git clone https://github.com/AwAiS-ahmd/Keeper-App.git
cd Keeper-App
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to the provided local URL (typically http://localhost:5173)

## Usage

1. **Add Notes:** Use the form at the top to enter a title and content, then click "Add" to create a note
2. **View Notes:** All created notes appear as cards below the form
3. **Delete Notes:** Click the delete button on any note card to remove it
4. **Search:** Use the search bar in the navbar to filter notes (UI implemented, search logic can be extended)

## Project Structure

```
src/
├── main.jsx                          # React entry point
├── App.jsx                           # Main application component
├── App.css                           # Main styling
├── index.css                         # Global styles
└── KeeperApp-Components/
    ├── KeeperManager.jsx             # State management and layout
    ├── Header.jsx                    # App header with title
    ├── Navbar.jsx                    # Navigation bar with search
    ├── Form.jsx                      # Note creation form
    ├── Note.jsx                      # Individual note card component
    ├── Footer.jsx                    # Footer with copyright
    └── Navbar.css                    # Navbar styling
```

## Technology Stack

- **Frontend Framework:** React 19.0.0
- **Build Tool:** Vite 6.3.1
- **Styling:** CSS3 (with animations and gradients)
- **Icons:** Font Awesome 6.5.1
- **Development Tools:** ESLint, Vite React Plugin

## License

This project is not licensed. All rights reserved.