Getting Started

Canada Football Association Club Dashboard

Developed with:

React - 18.2.0

Node.js - 18.12.1

This dashboard is designed for the Canada Football Association Club to manage and track team performance, goals, matches, and other essential football-related statistics.

Installation

First, install the dependencies using:

yarn install
# OR
npm install --legacy-peer-deps

Then, run the development server:

yarn start
# OR
npm run start

Then, open http://localhost:3000 in your browser to see the dashboard.

Ensure you have the latest stable version of Node.js installed. If you need multiple versions of Node.js, use nvm.

Available Scripts

The Canada Football Association Club Dashboard is based on the Create-React-App template.

start

Runs the app in development mode. Open http://localhost:3000 to view it in your browser.

build

Builds the app for production in the build folder, optimizing performance and minifying the files.

gzip

Builds the app for production and compresses it with gzip and brotli to reduce transfer size.

eject

Warning: This is irreversible. Running eject gives full control over the configuration (Webpack, Babel, ESLint, etc.).

Customizing Icons

You can import selection.json from src/fonts/icomoon into the IcoMoon app for managing custom icons.

Google Analytics Integration

To integrate Google Analytics, create a new project on Google Analytics and obtain the tracking ID.

Create a new .env.local file in the root directory and add:

REACT_APP_PUBLIC_GA=YOUR_TRACKING_ID

File Structure

.
├── public                  # Static files
│   ├── favicon.ico
│   ├── index.html          # Main HTML file
│   ├── robots.txt
├── src                     # Source files
│   ├── app                 # Redux store
│   ├── assets              # Static assets
│   ├── components          # Reusable components
│   ├── constants           
│   ├── contexts            # Context providers
│   ├── db                  # Database (fixtures, matches, goals tracking)
│   ├── features            # Redux slices
│   ├── hooks               # Custom hooks
│   ├── layout              # Layout components (header, sidebar, etc.)
│   ├── pages               # Dashboard pages
│   ├── styles              # Global styles
│   ├── ui                  # UI components
│   ├── utils               # Helper functions
│   ├── widgets             # Reusable widgets (score tracker, match highlights, etc.)
│   ├── App.js              # Main app component
│   ├── index.js            # App entry point
│   ├── layouts.js          # Grid layouts for statistics
│   ├── style.scss          # Global styles
├── .htaccess               # Apache config
├── craco.config.js         # Custom CRA config
├── package.json            

Third-party Libraries

React-spring - Animations

Recharts - Charts for player and team stats

React-select

Swiper - Match highlights carousel

React-toastify - Notifications

MUI - UI components

styled-components - CSS-in-JS styling

dnd-kit - Drag-and-drop interactions

React Redux - State management

React Router - Routing

React Grid Layout - Dashboard layout

React Hook Form - Form handling

React Big Calendar - Match and event scheduling

