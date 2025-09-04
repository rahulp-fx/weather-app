# 🌦️ Weather App

A sleek, responsive weather application built with **React + Vite**, delivering real-time forecasts and weather insights with speed and style.  

👉 **[Live Demo](https://weather-app-nine-eta-31.vercel.app)**  

---

## ✨ Features
- 🌍 Search weather by **city name**
- 📡 Real-time weather data (via OpenWeatherMap API or chosen service)
- 🌡️ Displays:
  - Current temperature, humidity, wind speed, and pressure  
  - Weather condition with icons  
  - (Optional) Forecast for upcoming days
- 📱 **Responsive design** for mobile, tablet, and desktop
- ⚡ Fast load times (thanks to Vite + React)

---

## 🚀 Live Preview
Check it out here:  
👉 [weather-app-nine-eta-31.vercel.app](https://weather-app-nine-eta-31.vercel.app)

---

## 🛠️ Installation & Setup

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or later)
- npm or yarn

### Steps
```bash
# Clone the repo
git clone https://github.com/rahulp-fx/weather-app.git

cd weather-app

# Install dependencies
npm install
# or
yarn install

# Create a .env file at root and add:
VITE_WEATHER_API_KEY=your_api_key_here
VITE_WEATHER_API_URL=https://api.openweathermap.org/data/2.5

# Run locally
npm run dev
```

Then visit: `http://localhost:5173`

### Build for Production
```bash
npm run build
```
Your app will be bundled inside the `dist/` folder, ready for deployment.

---

## 🧩 Tech Stack
- **Frontend**: React (Vite)  
- **Styling**: (Tailwind CSS / CSS / your choice)  
- **API**: OpenWeatherMap (or whichever you used)  
- **Deployment**: [Vercel](https://vercel.com/)  

---

## 📂 Folder Structure
```
weather-app/
├── public/
│   └── index.html
├── src/
│   ├── components/    # Reusable UI components
│   ├── services/      # API helpers
│   ├── App.jsx
│   └── main.jsx
├── .env
├── package.json
└── vite.config.js
```

---

## 🤝 Contributing
Contributions are welcome!  
1. Fork it 🍴  
2. Create your feature branch: `git checkout -b feature/my-new-feature`  
3. Commit changes: `git commit -m 'Add something'`  
4. Push to branch: `git push origin feature/my-new-feature`  
5. Open a Pull Request 🎉  

---

## 📜 License
Distributed under the **MIT License**. See `LICENSE` for details.

---

## 👨‍💻 Author
Made with ❤️ by **Rahul**  
🔗 [GitHub](https://github.com/rahulp-fx)  
