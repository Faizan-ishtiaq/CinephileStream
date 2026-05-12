<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=e50914&height=200&section=header&text=CinephileStream&fontSize=60&fontColor=ffffff&fontAlignY=35&desc=Your%20Ultimate%20Movie%20%26%20TV%20Explorer&descAlignY=55&descSize=20" width="100%"/>

<br/>

[![Live Demo](https://img.shields.io/badge/🎬%20Live%20Demo-CinephileStream-e50914?style=for-the-badge&logoColor=white)](https://chinephile-stream.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Faizan--ishtiaq-181717?style=for-the-badge&logo=github)](https://github.com/Faizan-ishtiaq)
[![Made with React](https://img.shields.io/badge/Made%20with-React-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org)
[![Tailwind CSS](https://img.shields.io/badge/Styled%20with-Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com)

<br/>

> **A Netflix-inspired movie & TV show explorer built with React, powered by the TMDB API.**  
> Browse, search, and discover thousands of movies and series — all in one place.

<br/>

</div>

---

## 🎥 Preview

<div align="center">

| Home Page | Movies Section | Search |
|-----------|---------------|--------|
| Rows of popular, top rated & upcoming content | Filter by Popular, Top Rated, Now Playing, Upcoming | Live search with instant suggestions |

</div>

---

## ✨ Features

- 🏠 **Home Page** — Multiple rows of curated content (Popular, Top Rated, Upcoming, Airing Today)
- 🎬 **Movies Section** — Browse by Popular / Top Rated / Now Playing / Upcoming
- 📺 **TV Shows Section** — Browse by Popular / Airing Today / On The Air / Top Rated
- 🔍 **Live Search** — Instant search suggestions with poster thumbnails as you type
- 📄 **Pagination** — Navigate through pages of results
- 🖱️ **Hover Details** — See rating, release year & overview on card hover
- ▶️ **Watch Now** — One-click to stream any movie or show
- 📱 **Fully Responsive** — Works seamlessly on mobile, tablet & desktop
- 🎠 **Swiper Sliders** — Smooth horizontal scrolling rows

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React** | UI & Component Architecture |
| **Vite** | Lightning-fast build tool |
| **Tailwind CSS** | Styling & Responsive Design |
| **Swiper.js** | Horizontal card sliders |
| **React Router DOM** | Client-side routing |
| **TMDB API** | Real movie & TV show data |
| **Custom `useFetch` Hook** | Data fetching with debounce |

---

## 📁 Project Structure

```
CinephileStream/
├── src/
│   ├── api/
│   │   └── Tmdb.js            # API keys & base URLs
│   ├── components/
│   │   ├── Navbar.jsx          # Navigation + live search
│   │   ├── Home.jsx            # Homepage with all rows
│   │   ├── MovieRow.jsx        # Swiper slider row
│   │   ├── MediaList.jsx       # Movies/TV grid with filters
│   │   ├── Movies.jsx          # Movies page
│   │   └── TvShows.jsx         # TV Shows page
│   ├── Hooks/
│   │   └── useFetch.js         # Custom data fetching hook
│   └── App.jsx                 # Routes & global state
├── index.html
├── package.json
└── vite.config.js
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- Free TMDB API key from [themoviedb.org](https://www.themoviedb.org/)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Faizan-ishtiaq/ChinephileStream.git

# 2. Navigate into the project
cd ChinephileStream

# 3. Install dependencies
npm install

# 4. Add your TMDB API key in src/api/Tmdb.js
export const API_KEY = "your_api_key_here"

# 5. Start the development server
npm run dev
```

---

## 🌐 Live Demo

👉 **[chinephile-stream.vercel.app](https://chinephile-stream.vercel.app)**

Deployed on **Vercel** for fast, global access.

---

## 🙋‍♂️ About Me

Hi, I'm **Faizan Ishtiaq** — a passionate Frontend Developer from **Lahore, Pakistan** 🇵🇰

I love building real-world projects that combine clean UI with real data. CinephileStream is my first React + Tailwind project and I'm proud of what I built — TMDB API integration, live search, pagination, responsive design, and more.

I'm currently **open to internship and job opportunities** in frontend development.

---

## 📬 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Faizan--ishtiaq-181717?style=for-the-badge&logo=github)](https://github.com/Faizan-ishtiaq)

</div>

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=e50914&height=100&section=footer" width="100%"/>

⭐ **If you like this project, please give it a star!** ⭐

**Made with ❤️ by Faizan Ishtiaq**

</div>
