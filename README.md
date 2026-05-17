# ☀️ SolarCore_Mamun

A real-time industrial solar power monitoring dashboard built with **Flask + SQLite + Chart.js**, designed for simulation systems and future IoT integration.


# 🚀 Quick Start

```bash
cd solar_monitor
pip install flask
python app.py

Open in browser:

http://localhost:5000
⚡ Features
🔴 Live Data Monitoring

Real-time monitoring of:

Voltage
Current
Power
Battery
Temperature

⏱ Auto refresh every 2 seconds

📊 Multi-Panel Dashboard

Includes:

Analytics Panel
Alert System
Admin Controls
Activity Logs
📈 Real-Time Graphs

Dynamic charts powered by Chart.js:

Power Trend Analysis
Battery History
System Analytics
🎛️ Industrial Arc Gauges UI

Smooth animated industrial-style gauges for:

Voltage
Current
Battery
Temperature
⚠️ Fault Simulation Engine

Supports:

Over Voltage (OVV)
Under Voltage (UVV)
Over Temperature Cutoff (OTC)
Ground Fault (GRD)
🗄️ SQLite Logging System
Persistent sensor storage
Historical tracking
Lightweight database system
📥 CSV Export

Export historical reports directly as CSV files.

🌙 Dark / Light Mode
Persistent theme switching
User-friendly interface
📱 Responsive Design

Optimized for:

Desktop
Tablet
Mobile Devices
📁 Project Structure
solar_monitor/
├── app.py                # Flask backend + simulation engine
├── solar_monitor.db      # SQLite database
├── requirements.txt
├── templates/
│   └── index.html        # Dashboard UI
└── static/
    ├── css/
    │   └── style.css     # UI styling
    └── js/
        └── main.js       # Charts & live updates
🔌 API Endpoints
Endpoint	Method	Description
/api/live	GET	Current sensor readings
/api/history?minutes=60	GET	Historical data
/api/alerts	GET	System alerts
/api/alerts/acknowledge	POST	Acknowledge alerts
/api/stats	GET	Daily statistics
/api/export?hours=24	GET	Export CSV reports
🧠 Tech Stack
Backend: Flask (Python)
Database: SQLite
Frontend: HTML, CSS, JavaScript
Visualization: Chart.js
Architecture: REST API + Real-time Polling
🏗️ System Highlights

✔ Real-time simulation engine
✔ Industrial monitoring dashboard
✔ Lightweight backend architecture
✔ Easy IoT integration support
✔ ESP32 / Arduino / Raspberry Pi ready

👨‍💻 Developer Notes

This project is designed for:

Industrial simulation systems
Renewable energy monitoring
Academic final-year projects
Portfolio-level software showcase
IoT dashboard development
📌 Project Tag
SolarCore_Mamun
