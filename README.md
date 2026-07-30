# ⛅ SkyCast – A Full-Stack Weather Application

SkyCast is a full-stack weather application built with Next.js that delivers real-time weather conditions, hourly and daily forecasts, air quality information, and interactive map-based location search. By combining Server-Side Rendering (SSR) and Client-Side Rendering (CSR), it provides fast performance, improved SEO, and a seamless user experience.

---

## ✨ Features

### 1. 🌤️ Real-Time Weather & Forecasts
Integrated WeatherAPI to provide current weather conditions, hourly forecasts, daily forecasts, and air quality information.

### 2. 🗺️ Interactive Location Search
Implemented location search with a customized Leaflet map, allowing users to search for locations or select them directly from the map to view weather information.

### 3. 🚀 Optimized Rendering & SEO
Leveraged Next.js Server-Side Rendering (SSR), Client-Side Rendering (CSR), pre-rendering, and dynamic metadata generation to improve performance and search engine optimization.

### 4. ⚡ Efficient Data Fetching
Implemented server-side and client-side data fetching using React Query and Axios to enable efficient API communication and improved application performance.

### 5. 🎨 Modern User Interface
Enhanced the user experience with smooth Framer Motion animations, reusable animation HOCs, and flexible React Icons for an engaging interface.

### 6. 🏗️ Application Architecture
Managed application state using the Context API and utilized Next.js API Routes to securely handle client-server communication.

---

## 🛠️ Tech Stack

Next.js, React.js, Typescript, Tailwind CSS, Framer Motion, Leaflet.js, React Query, Axios, React Icons

---

## ⚙️ Usage

### 🔑 Environment Variables

Create a `.env` file in the root directory and add the following variables:

```env
WEATHERAPI_APIKEY=your_api_key_here  # (Create one at https://www.weatherapi.com/)

# Enable API to get real data or use mock data
# 1: true, 0: false
ENAPI=1   # set to 1 to enable API, 0 to use mock data
```

| Variable | Description | Values |
|----------|-------------|--------|
| `WEATHERAPI_APIKEY` | Your API key from [WeatherAPI](https://www.weatherapi.com/) | String |
| `ENAPI` | Toggle between live API data and mock data | `1` = enabled, `0` = disabled |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/prabinb50/SkyCast-WeatherApp.git

# Navigate into the project directory
cd SkyCast-WeatherApp

# Install dependencies
npm install

# Run the development server
npm run dev
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request

---

## 📄 License

This project is open source and available for learning purposes.