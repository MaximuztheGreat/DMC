# Firebase Books Review App - Replit Setup

## Overview
This is a Firebase-hosted web application that allows users to browse books and write reviews. The app uses Firebase Authentication (anonymous sign-in) and Firestore for storing reviews.

## Project Architecture
- **Frontend**: Static HTML/CSS/JavaScript using Materialize CSS framework
- **Backend**: Firebase services (Auth + Firestore)
- **Data**: Static book catalog stored in JSON file
- **Deployment**: Configured for Replit autoscale deployment

## Recent Changes (September 18, 2025)
- Successfully imported from GitHub and configured for Replit environment
- Modified package.json to use http-server for local development instead of Firebase CLI
- Configured server to bind to 0.0.0.0:5000 for Replit proxy compatibility
- Set up workflow for frontend development server
- Configured production deployment settings

## Key Files
- `public/index.html` - Main application HTML
- `public/auth.js` - Firebase authentication handling
- `public/data.js` - Data fetching and Firestore operations
- `public/firebaseConfig.js` - Firebase project configuration
- `public/books.json` - Static book catalog data
- `firebase.json` - Firebase hosting configuration
- `package.json` - Dependencies and scripts

## Development
- Run `npm start` to start the development server
- Server runs on port 5000 and binds to all hosts (0.0.0.0)
- Uses http-server for static file serving with CORS enabled

## User Preferences
- Frontend configured for Replit environment with proper host binding
- Using static HTTP server instead of Firebase CLI for development