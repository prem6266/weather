# 🌤️ Weather App

A responsive React-based weather application that provides real-time weather data with geolocation support, search history, and dark/light theme.

🔗 **Live Demo:** https://weather-blond-beta.vercel.app  
📁 **GitHub:** https://github.com/prem6266/weather

---

## 🏷️ Badges

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## ✨ Features

- 🔍 Search weather information by city name
- 🌡️ View current weather and forecasts
- 📍 Geolocation support for local weather
- 🕐 Save & view search history
- 🌙 Dark / Light theme support
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| ⚛️ Framework | React + TypeScript |
| ⚡ Build Tool | Vite |
| 🎨 Styling | Tailwind CSS |
| 🌐 API | WeatherAPI |
| 🔄 Data Fetching | React Query |
| 🚀 Deployment | Vercel |

---

## 💡 What I Learned

- ⚛️ **React Query** — Efficient server state management with caching & background refetching
- 🧠 **TypeScript** — Writing type-safe API interfaces and custom hooks
- 🪝 **Custom Hooks** — Built reusable hooks for weather, geolocation & local storage
- 📍 **Geolocation API** — Accessing browser geolocation with proper error handling
- ⚡ **Vite** — Fast development build tool setup and configuration
- 🎯 **Debounced Search** — Optimized search to reduce unnecessary API calls
- 🌙 **Theme Switching** — Implemented dark/light mode with persistent user preference

---

## 🧭 My Approach

1️⃣ Planned the app structure around reusable custom hooks  
2️⃣ Set up Vite + React + TypeScript for a fast dev environment  
3️⃣ Integrated WeatherAPI for real-time weather data  
4️⃣ Built geolocation support with proper fallback handling  
5️⃣ Used React Query for smart data caching & performance  
6️⃣ Added local storage for search history persistence  
7️⃣ Implemented dark/light theme toggle  
8️⃣ Deployed on Vercel & made it live ✅  

---

## ✅ Best Practices Implemented

### 🔷 Type Safety
- TypeScript interfaces for all API responses
- Strict type checking throughout the codebase
- Type-safe custom hooks

### ⚡ Performance Optimization
- React Query for intelligent data caching
- Debounced search to reduce API calls
- Lazy loading of components

### 🚨 Error Handling
- API error handling with fallback UI
- Geolocation permission error handling
- User-friendly error messages

### 🗃️ State Management
- Local storage for persistent search history
- React Query for server state
- Custom hooks for reusable logic

---

## 🚀 Getting Started

```bash
git clone https://github.com/prem6266/weather.git
cd weather
```

Create a `.env` file in root directory:

```env
VITE_WEATHER_API_KEY=your_api_key_here
VITE_WEATHER_API_URL=https://api.weatherapi.com/v1
```

Then install and run:

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📂 Project Structure

```
/src/api    → API configuration and requests
/src/hooks  → Custom hooks for weather, geolocation & storage
/src/pages  → Page components
/src/lib    → Utility functions and helpers
```

---

## 👨‍💻 Author

**Prem Kumar Joshi**  
[![GitHub](https://img.shields.io/badge/GitHub-prem6266-181717?style=flat&logo=github&logoColor=white)](https://github.com/prem6266)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/prem-kumar-joshi)
