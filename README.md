Kumasi Air Quality – Interactive Dashboard 🌍

An interactive heatmap of PM2.5 levels across Kumasi with a time slider.
Built using Leaflet + Leaflet.heat + GitHub Pages with demo time-series air quality data.

This project demonstrates how open geospatial dashboards can support health, environment, and policy planning.

🔹 Live Demo

👉 Explore the dashboard

🔹 Preview

🔹 Features

🗺️ Interactive Heatmap of PM2.5 levels across Kumasi.

⏳ Time Slider to explore day-by-day changes.

📍 Station Popups with PM2.5, PM10, and AQI readings.

📱 Mobile-friendly, fast, and shareable via GitHub Pages.

💡 CTA for clients: “Need a live dashboard? Let’s talk.”

🔹 Data

Source: Demo data generated for 4 monitoring stations in Kumasi (7-day series).

File: data/air_quality_timeseries.json

Format:

{
  "station": "KNUST Campus",
  "lat": 6.673,
  "lon": -1.571,
  "values": [
    { "date": "2025-09-01", "pm25": 45, "pm10": 70, "aqi": 85 },
    { "date": "2025-09-02", "pm25": 60, "pm10": 90, "aqi": 110 }
  ]
}

🔹 Tech Stack

Leaflet for mapping

Leaflet.heat for heatmap visualization

GeoJSON/JSON for time-series data

GitHub Pages for free hosting

🔹 Why It Matters

Air pollution is a pressing urban issue.
This dashboard demonstrates how simple web tools can:

Help city planners locate pollution hotspots

Support health organizations with awareness tools

Provide citizens with easy-to-understand risk maps

🔹 Next Steps

✅ Add real-time data via OpenAQ
 or local sensors

✅ Extend to include other pollutants (NO2, CO)

✅ Connect to SMS/alerts for health advisories

✉️ Built by Victor Morton-Bruce
Open to collaborations in GIS, environment, and digital storytelling.