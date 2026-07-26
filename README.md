# 🌤️ Weather Intelligence Web Application

An interactive, responsive, single-page Weather Intelligence Web Application built using **React**, **Vite**, and **Tailwind CSS**. The app utilizes the free and open **Open-Meteo APIs** to deliver real-time weather metrics, 7-day forecasts, and automated smart planning recommendations.

---

## 🌟 Live Demo & Resources

- **Live Application:** [https://00cbf15d-stackai2.vasanth-ravichan.workers.dev/](https://00cbf15d-stackai2.vasanth-ravichan.workers.dev/)
- **GitHub Repository:** [https://github.com/vasanthravichanderan/stackai](https://github.com/vasanthravichanderan/stackai)
- **AI Studio App Builder:** [View in Google AI Studio](https://aistudio.google.com/apps/3b694b8c-9215-4803-8ca4-d41dc566f594?showPreview=true&showAssistant=true)

---

## 🚀 Features

### 1. City Search & Geocoding
- **Location Lookup:** Allows users to search for any city globally.
- **Geocoding API:** Translates city names into exact latitude and longitude coordinates using the Open-Meteo Geocoding API (`https://geocoding-api.open-meteo.com/v1/search?name=`).

### 2. Live Weather Data & 7-Day Forecast
- **Real-Time Weather Metrics:** Fetches current temperature, weather state (sunny, rainy, cloudy, etc.), humidity, and wind speed using the Open-Meteo Forecast API (`https://api.open-meteo.com/v1/forecast`).
- **7-Day Outlook:** Displays clean forecast cards showing daily high and low temperatures along with visual condition indicators.

### 3. Smart Planning Recommendations
- **Automated Insights:** Analyzes upcoming condition codes to provide actionable daily advice:
  - ☔ **Rain/Storm Warning:** Suggests carrying an umbrella or wearing waterproof gear.
  - ☀️ **High UV / Heat Alert:** Recommends sunscreen and light clothing on hot days.
  - ❄️ **Cold/Snow Warning:** Highlights heavy coats or layering requirements.

### 4. Robust Error Handling & Public API Compliance
- **Graceful Error Recovery:** Safely catches empty queries, invalid city names, or network request timeouts and displays user-friendly alert badges (e.g., *"City not found or network error. Please check spelling and try again."*).
- **Zero API Keys:** Uses 100% public Open-Meteo endpoints—no secret credentials, hidden environment variables, or private keys required.

---

## 🛠️ Tech Stack

- **Build Tool / Bundler:** [Vite](https://vitejs.dev/)
- **Frontend Library:** [React](https://react.dev/)
- **Styling Utility:** [Tailwind CSS](https://tailwindcss.com/)
- **Data Source:** [Open-Meteo Free Weather API](https://open-meteo.com/)
- **Deployment & Hosting:** Cloudflare Pages

---

## 💻 Local Setup & Development

Follow these steps to run the application locally on your machine:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/vasanthravichanderan/stackai.git](https://github.com/vasanthravichanderan/stackai.git)
   cd stackai
