# 🎵 React Music Player - Shazam Clone 🎧

This is a fully responsive and modern music player application built using **React**, **Vite**, and **Redux Toolkit**. It utilizes the **Shazam Core API** from RapidAPI to fetch real-time music data like top charts, artist info, and song previews.

---

## 🚀 Features

- 🔍 Discover Top Charts and Songs by Country
- 🎙 Explore Songs by Artist and Genre
- 🔊 Play and pause songs with real-time audio controls
- 📱 Responsive design (mobile-friendly)
- 🌐 Uses [Shazam Core API](https://rapidapi.com/) for music data
- ⚡ Built with Vite for lightning-fast dev experience

---

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS
- **State Management**: Redux Toolkit + RTK Query
- **Routing**: React Router DOM
- **Audio Player**: HTML5 Audio API
- **API**: Shazam Core API (RapidAPI)
- **Build Tool**: Vite

---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add your RapidAPI credentials:

```env
VITE_SHAZAM_CORE_RAPID_API_KEY=your_rapidapi_key_here
VITE_GEO_API_KEY=your_geo_api_key_if_used
