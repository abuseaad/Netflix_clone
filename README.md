# 🎬 Netflix Clone

A responsive Netflix-style home page built with **React 19**, **Vite**, and the **TMDB API**.

![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?style=flat-square&logo=vite&logoColor=white)
![Swiper](https://img.shields.io/badge/Swiper-14-6332F6?style=flat-square&logo=swiper&logoColor=white)
![TMDB](https://img.shields.io/badge/TMDB-API-01B4E4?style=flat-square&logo=themoviedatabase&logoColor=white)

> Educational project, not affiliated with Netflix. Data and images are provided by [TMDB](https://www.themoviedb.org/).

## ✨ Features

- **Hero banner**: shows a random Netflix Original with its title, overview, and Play / More Info buttons
- **Sticky navbar**: changes style on scroll, with a search toggle, notification badge, and profile menu
- **Swipeable rows**: Trending, Popular on Netflix, Action, and Top Rated, built with Swiper
- **Hover movie cards**: preview image with action buttons, rating, quality, and genre tags
- **Responsive**: header and footer adapt to smaller screens

## 🛠️ Tech Stack

React 19 · Vite 8 · Axios · Swiper · React Router · Lucide / React Icons · CSS Modules · ESLint

## 🚀 Getting Started

**Requirements:** Node.js 20+ and a free [TMDB API key](https://www.themoviedb.org/settings/api).

```bash
git clone https://github.com/abuseaad/Netflix_clone.git
cd Netflix_clone
npm install
```

Create a `.env` file in the project root:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key_here
```

Start the app:

```bash
npm run dev
```

Open <http://localhost:5173>.

> Never commit your `.env` file. It is already in `.gitignore`.

## 📜 Scripts

| Command | Description |
| :--- | :--- |
| `npm run dev` | Start the development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint |

## 📁 Project Structure

```text
src/
├── assets/image/        # Logo and images
├── Components/
│   ├── Banner/          # Hero banner
│   ├── DisplayRow/      # Fetches data and renders rows
│   ├── Footer/
│   ├── Header/          # Navbar, search, profile menu
│   ├── MovieCard/       # Poster + hover preview
│   ├── SlideShow/       # Swiper carousel
│   └── sign/            # Sign in / out (placeholders)
├── Utility/
│   ├── MovieInstance.jsx  # Axios instance
│   └── requestUrls.js     # TMDB endpoints
├── App.jsx
└── main.jsx
```

## 🗺️ Roadmap

- [ ] Working search
- [ ] Sign in / sign out
- [ ] Movie details page with trailers
- [ ] Real genres on hover cards
- [ ] Remaining rows (Comedy, Horror, Romance, Documentaries)

## 👤 Author

**Sadik Jemal** 