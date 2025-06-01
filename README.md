# 🌍 Chat with Maps

## 📌 Abstract

**Problem Statement:**
Travelers and users often find it hard to discover nearby essential services, tourist attractions, or make trip plans in a personalized and interactive way—especially in local languages.

**Solution:**
"Chat with Maps" is an AI-powered interactive map-based assistant that:

- Understands voice or text-based user queries
- Identifies location + place types using Gemini AI
- Retrieves real-time places, weather, and visualizations
- Offers a trip planner + correlation explorer
- Supports multiple Indian and global languages

**Key Features:**

- 🗣️ Voice input for queries and follow-ups
- 🌐 Language selection (Indian + Global)
- 📍 Google Maps + OpenWeatherMap integration
- 🧠 Gemini-powered smart intent understanding
- 📊 Charts: Place visits, weather trends, distance
- 🧳 Trip planner that generates day-wise itineraries
- 🔄 Follow-up question support on same location
- 🔗 Correlation explorer for activities and suggestions

---

## 🚀 What This App Does

- Accepts a travel-related query (e.g. "Show me beaches and cafes in Goa")
- Uses Gemini AI to extract location and place types
- Shows an interactive map with ratings, reviews, photos
- Fetches and plays weather info with TTS
- Visualizes analytics using Plotly charts
- Allows follow-up questions and trip planning

---

## 🛠️ How to Run Locally

### 1. Clone this repo

```bash
git clone https://github.com/Abinayashri-Gupta/ChatWithMaps.git
cd chat-with-maps
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add your API keys to `.streamlit/secrets.toml`

Create a file `.streamlit/secrets.toml` and paste:

```toml
GOOGLE_MAPS_API_KEY = "your_google_maps_api_key"
GEMINI_API_KEY = "your_gemini_api_key"
OPENWEATHERMAP_API_KEY = "your_openweathermap_api_key"
```

### 4. Run the app

```bash
streamlit run app.py
```

---

## 🌐 How to Deploy on Streamlit Cloud

1. Push the code to a GitHub repository
2. Go to [streamlit.io/cloud](https://streamlit.io/cloud)
3. Click **New App**
4. Choose your repo and branch
5. In the settings panel, go to the **"Secrets"** tab and paste your secrets from `.streamlit/secrets.toml`
6. Click **Deploy**

---

## 📫 Contact

> Built by Abinayashri Gupta (📧 abinayashrigupta05@gmail.com)

© 2025 Chat With Maps – All rights reserved.
