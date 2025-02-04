# Weather App

A React-based weather application that allows users to:
- Search for weather information by city name
- View current weather and forecasts
- Save search history
- Use geolocation for local weather

## Features

- Real-time weather data using WeatherAPI
- Geolocation support
- Search history with local storage
- Responsive design
- Dark/light theme support

## Tech Stack

- React + TypeScript
- Vite
- TailwindCSS
- WeatherAPI
- React Query for data fetching

## Project Setup

1. Clone the repository
2. Create a `.env` file in the root directory with:
   ```
   VITE_WEATHER_API_KEY=your_api_key_here
   VITE_WEATHER_API_URL=https://api.weatherapi.com/v1
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start development server:
   ```bash
   npm run dev
   ```

## Project Structure

- `/src/api` - API configuration and requests
- `/src/hooks` - Custom hooks for weather, geolocation, and storage
- `/src/pages` - Page components
- `/src/lib` - Utility functions and helpers

## Development Approach

This weather app was built with a focus on:
- Clean, maintainable code structure
- Type safety with TypeScript
- Reusable custom hooks
- Local storage for persistent data
- Error handling and loading states

#Best Practices Implemented


## Type Safety
- TypeScript interfaces for API responses
- Strict type checking
- Type-safe custom hooks

## Performance Optimization
- React Query for caching
- Debounced search
- Lazy loading of components

## Error Handling
- API error handling
- Geolocation error handling
- Fallback UI components

## State Management
- Local storage for persistence
- React Query for server state
- Custom hooks for reusable logic
