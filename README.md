# 🎧 Spotify Clone - React Music Streaming App 🎶

A modern and responsive **Spotify-style music streaming app** built with **React**, **Vite**, **Tailwind CSS**, and **Redux Toolkit**. This project uses the **Shazam Core API** from RapidAPI to stream music, show trending tracks, and explore artists — all within a slick, Spotify-like UI.

---

## 🚀 Features

- 🎵 Browse top charts and trending music by country or genre
- 🔍 Search for songs, artists, and albums
- 👤 View artist profiles and related tracks
- ⏯️ Real-time audio player with play, pause, next, and previous controls
- 📱 Fully responsive layout — works on all screen sizes
- ⚡ Built with Vite for fast development experience

---

## 🔧 Tech Stack

- **Frontend**: React, Tailwind CSS, Vite
- **State Management**: Redux Toolkit + RTK Query
- **API**: Shazam Core API from RapidAPI
- **Routing**: React Router DOM
- **Audio**: HTML5 Audio API

---

## 🌐 APIs Used

- **Shazam Core API** → for real-time music data
- **Geo API** (optional) → to detect user’s location and display local top charts

---

## 📂 Environment Setup

Create a `.env` file in the root directory:

```env
VITE_SHAZAM_CORE_RAPID_API_KEY=your_rapidapi_key_here
VITE_GEO_API_KEY=your_geo_api_key_here
