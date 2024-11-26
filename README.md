# Air Quality Index (AQI) Tracker 🌍💨
- Recently, the AQI levels in Delhi and its surrounding areas have been making headlines for all the wrong reasons. 
- With air pollution worsening and people scrambling for data to understand their local air quality, I decided to build this fun little project that not only fetches real-time AQI data but also ensures accuracy with custom-calculated AQI values.



# Key Features
- **Geolocation-Based AQI**: Automatically detects your location to fetch relevant air quality data.
- **Custom AQI Calculation**: Implements precise AQI threshold logic for PM2.5 and PM10 pollutants.
- **User-Friendly Interface**: Built with Tailwind CSS for a sleek, responsive, and clean design.
- **Real-Time Data**: Fetches up-to-date air quality information using the *WAQI API*.
# 📷 

### 🚀 Technologies Used
- Frontend: React with functional components and hooks.
- Styling: Tailwind CSS for a responsive and modern UI.
- API: WAQI API for air quality data.
- Notifications: Toast alerts for errors and status updates (Sonner).

# 🛠️ How to Run
- **Clone the Repository**:


```bash
git clone https://github.com/yourusername/aqi-tracker.git  
cd aqi-tracker
```

- **Install Dependencies**:

```bash
npm install  
```

- **Set API Key**:



```bash
VITE_WAQI_API_KEY=your_api_key_here  
```
- **Run the App**:
```bash
npm run dev
```  

# 📊 How it Works
- The app uses the Geolocation API to get the user's latitude and longitude.
- Fetches AQI data for the given location using the WAQI API.
- Implements custom logic to calculate AQI for PM2.5 and PM10 based on EPA standards.
- Displays the highest pollutant's AQI value along with pollutant-specific details.
