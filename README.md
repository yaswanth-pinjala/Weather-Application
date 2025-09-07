🌦️ Weather Forecasting Application

A simple and responsive Weather Forecasting Application built with React.js and the OpenWeatherMap API. This project provides real-time weather updates, including temperature, humidity, wind speed, and weather conditions, with an intuitive and user-friendly interface.

🚀 Features
  🌍 Search weather by city name
  🌡️ Displays temperature, humidity, and wind speed
  ☁️ Dynamic weather icons based on real-time conditions
  ⚡ Fast and responsive UI with Vite + React
  🔒 API key secured with .env file
  🎨 Clean and modern design using CSS
  
🛠️ Tech Stack
  Frontend: React.js, Vite
  Styling: CSS (with Google Fonts)
  API: OpenWeatherMap API
  Deployment: Vercel / Netlify

📂 Project Structure
weather-app/
│
├── src/
│   ├── assets/            # Icons and images
│   ├── components/        # React components
│   │   └── Weather.jsx
│   ├── App.jsx            # Main app component
│   ├── main.jsx           # Entry point
│   ├── index.css          # Global styles
│   └── Weather.css        # Component-specific styles
│
├── .env                   # Environment variables (API key)
├── package.json           # Dependencies & scripts
└── vite.config.js         # Vite configuration

⚙️ Installation & Setup

Clone the repository:
>> git clone https://github.com/your-username/weather-app.git
>> cd weather-app

Install dependencies:
>> npm install

Add your OpenWeatherMap API key in a .env file:
>> VITE_APP_ID=your_api_key_here

Start the development server:
>> npm run dev

Open your browser at:
>> http://localhost:5173

Screenshot of output:
<img width="1919" height="914" alt="Screenshot 2025-09-03 172344" src="https://github.com/user-attachments/assets/ee67af85-aae5-41a8-82b1-0153877bffdc" />

