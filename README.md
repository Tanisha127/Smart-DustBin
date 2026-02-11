# Smart-Dustbin IOT Dashboard

**Live Website:** https://iot-mini-project-eight.vercel.app/
This is a web-based IoT dashboard built using HTML, CSS, and JavaScript to monitor real-time sensor data from an ESP32-based Smart Waste Segregation System using the ThingSpeak API.

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
Then, open the project:
You can directly open:
`index.html`
in your browser.
Or use a Live Server extension (recommended in VS Code).
Open http://localhost:5500 (if using Live Server) with your browser to see the result.
You can start editing the dashboard by modifying:
`dashboard.html`
The page updates automatically if you are using Live Server.

## How It Works

This project connects to the ThingSpeak Cloud Platform to fetch real-time IoT data.
The ESP32 device:
- Collects distance data from an Ultrasonic Sensor
- Collects moisture data from a Soil Moisture Sensor
- Classifies waste as Dry (0) or Wet (1)
- Sends data to ThingSpeak

The dashboard:
- Fetches latest and historical data
- Displays real-time sensor values
- Shows dynamic graphs using Chart.js
- Auto-refreshes every 5 seconds

## Tech Stack

- HTML
- CSS
- JavaScript
- Chart.js
- ThingSpeak API
- ESP32

## Configuration

On the dashboard page:
- Enter your ThingSpeak Channel ID
- Enter your Read API Key (if the channel is private)
- Click Connect
The dashboard will begin fetching live data.

## Deployment

This project is a static website.
You can deploy it easily on: 
- Vercel
- Netlify
- GitHub Pages
Simply upload the project files and deploy.
