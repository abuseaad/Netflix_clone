# 🎬 Netflix Clone

A modern, responsive Netflix web application built with **React 19**, **Vite**, and **The Movie Database (TMDB) API**.

![React](https://img.shields.io/badge/React-19.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-8.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TMDB](https://img.shields.io/badge/TMDB-API-01B4E4?style=for-the-badge&logo=themoviedatabase&logoColor=white)
![Swiper](https://img.shields.io/badge/Swiper.js-14.x-6332F6?style=for-the-badge&logo=swiper&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-1.x-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

---

## 📖 Overview

This **Netflix Clone** is a responsive web application built with React and Vite. It integrates directly with **The Movie Database (TMDB) API** to fetch and display dynamic movie and TV show data in real-time, featuring interactive carousels, a dynamic hero banner, navigation scroll effects, and custom hover preview cards.

---

## ✨ Features

- **Dynamic Hero Banner**: Fetches and renders a random featured title from Netflix Originals with its backdrop, title, truncated description, and action buttons (*Play* & *More Info*).
- **Responsive Navigation Bar**:
  - Transparent header that smoothly darkens on window scroll.
  - Interactive search bar toggle.
  - Notification icon with indicator badge.
  - User profile menu dropdown (Account, Help Center, Sign Out).
- **Interactive Movie Rows (Carousels)**:
  - Multi-category rows including *Trending*, *Popular on Netflix*, *Action*, and *Top Rated*.
  - Smooth touch and click navigation powered by **Swiper.js**.
- **Netflix-Style Movie Cards**:
  - High-quality poster display.
  - Interactive hover state showing enlarged preview, play and list action buttons, age rating tags, and genre categories.
- **Responsive Layout**: Designed for seamless viewing across mobile devices, tablets, laptops, and desktop screens.
- **Multi-Column Footer**: Responsive 4-column footer with quick navigation links, social icons, and copyright details.

---

## 🛠️ Tech Stack

- **Frontend Framework**: React 19
- **Build Tool**: Vite 8
- **Data Fetching**: Axios
- **API**: The Movie Database (TMDB)
- **Carousels / Sliders**: Swiper.js
- **Icons**: Lucide React & React Icons
- **Styling**: CSS Modules (scoped styles)
- **Routing**: React Router DOM

---

## 📁 Project Structure

```
netflix/
├── public/
├── src/
│   ├── assets/
│   │   └── image/               # Static images and logos
│   ├── Components/
│   │   ├── Banner/              # Hero banner component & styles
│   │   ├── DisplayRow/          # Movie row container & API fetching
│   │   ├── Footer/              # Multi-column footer component
│   │   ├── Header/              # Navbar with search & profile dropdown
│   │   ├── MovieCard/           # Movie card with hover preview
│   │   ├── SlideShow/           # Swiper carousel wrapper
│   │   └── sign/                # Sign In / Sign Out components
│   ├── Utility/
│   │   ├── MovieInstance.jsx    # Axios instance for TMDB API
│   │   └── requestUrls.js       # TMDB API endpoint requests
│   ├── App.css
│   ├── App.jsx                  # Main application component
│   ├── index.css
│   └── main.jsx                 # Application entry point
├── .env                         # API keys (kept private)
├── package.json                 # Dependencies and scripts
└── vite.config.js               # Vite configuration
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (version 18 or higher recommended)
- `npm` or `yarn`
- A free API key from [The Movie Database (TMDB)](https://www.themoviedb.org/)

---

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sadikjemal/netflix-clone.git
   ```

2. **Navigate to the project folder**:
   ```bash
   cd netflix-clone
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Set up environment variables**:
   Create a `.env` file in the root of the project:
   ```env
   VITE_TMDB_API_KEY=your_actual_tmdb_api_key_here
   ```

5. **Start the development server**:
   ```bash
   npm run dev
   ```

6. **View the application**:
   Open your browser and navigate to `http://localhost:5173`.

---

## 🔑 Environment Variables

| Variable | Description |
| :--- | :--- |
| `VITE_TMDB_API_KEY` | Your TMDB API v3 key |

> **Note**: Never commit your `.env` file to GitHub. It is already added to `.gitignore`.

---

## 📜 Available Scripts

- `npm run dev` — Starts the local development server with Hot Module Replacement (HMR).
- `npm run build` — Bundles and optimizes the app for production.
- `npm run preview` — Previews the production build locally.
- `npm run lint` — Runs ESLint to check for code issues.

---

## 👨‍💻 Author

**Sadik J**

---

## 📝 License

This project is licensed free

