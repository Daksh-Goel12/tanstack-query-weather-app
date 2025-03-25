# 🌤️ TanStack Query Weather App

A weather application built with **Next.js** and **TanStack Query (React Query)** to fetch and display real-time weather data using the **OpenWeather API**. This app ensures efficient data fetching, caching, and automatic updates for a smooth user experience.

## 🚀 Features

- 🔍 **Search Weather by City Name**
- 🌍 **Real-time Weather Data**
- ⚡ **Optimized Data Fetching with TanStack Query**
- 🔄 **Automatic Data Updates & Caching**
- 📱 **Responsive UI with Tailwind CSS**
- 🌗 **Dark & Light Mode Support**

## 🛠️ Tech Stack

- **Frontend:** Next.js (React)
- **Data Fetching:** TanStack Query (React Query)
- **Weather API:** OpenWeather API 🌦️
- **Styling:** Tailwind CSS

## 📌 Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the repository:
```
git clone https://github.com/Daksh-Goel12/tanstack-query-weather-app.git
```

2️⃣ Navigate to the project directory:
```
cd tanstack-query-weather-app
```
3️⃣ Install dependencies:
```
npm install
```
4️⃣ Set up environment variables:

Create a .env.local file in the root directory and add your OpenWeather API Key:
```
NEXT_PUBLIC_WEATHER_API_KEY=your_openweather_api_key
```
🔹 Get your API key from OpenWeatherMap if you don’t have one.

5️⃣ Start the development server:
```
npm run dev
```

The app will be available at http://localhost:3000/.

🎯 Usage
- Enter a city name in the search bar.

- View real-time weather updates, including temperature, humidity, and weather conditions.

- The app fetches, caches, and updates data efficiently using TanStack Query.

🔥 Optimizations
- Automatic Data Refetching: Keeps weather data up-to-date.

- Error Handling & Loading States: Provides a seamless experience.

- Performance Optimization: Uses caching to reduce redundant API calls.

🤝 Contributing
- Contributions are welcome! To contribute:

- Fork the repository.

- Create a new branch (feature/your-feature-name).

- Commit your changes.

- Push to your branch.

- Create a Pull Request.
