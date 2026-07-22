# ❄️ VaxSafe AI – Cold Chain Monitoring System

![Python](https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-blue)
![Three.js](https://img.shields.io/badge/Three.js-3D-green)
![Chart.js](https://img.shields.io/badge/Chart.js-Visualization-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📌 Project Overview

**VaxSafe AI – Cold Chain Monitoring System** is a modern web-based dashboard designed to monitor vaccine storage temperatures in real time. The system helps ensure that vaccines remain within the recommended **cold chain temperature range (-2°C to +8°C)**, reducing the risk of spoilage and maintaining vaccine effectiveness.

The dashboard combines **real-time IoT monitoring**, **AI-based temperature analysis**, **3D visualization**, and **interactive charts** to provide an intuitive monitoring experience.

If a temperature exceeds the safe range, the system immediately generates visual and audio alerts along with AI-generated recommendations.

---

# 🎯 Objectives

- Monitor vaccine storage temperature in real time.
- Detect abnormal temperature conditions.
- Prevent vaccine spoilage.
- Provide AI-based recommendations.
- Display an interactive 3D cold storage model.
- Visualize historical temperature data.

---

# ✨ Features

## 🌡️ Real-Time Temperature Monitoring

- Live temperature updates
- Safe range detection
- Automatic status updates
- Real-time dashboard

---

## 🤖 AI Temperature Analysis

The AI engine analyzes temperature readings and provides recommendations such as:

- Temperature is safe
- Rising temperature warning
- Falling temperature warning
- Critical overheating alert
- Freezing alert
- Suggested corrective actions

---

## ❄️ Interactive 3D Cold Storage

Built using **Three.js**

Features include:

- Fully interactive 3D vaccine storage box
- Mouse drag rotation
- Floating animation
- Dynamic lighting
- Frost particle effects
- Opening lid during critical alerts
- Color changes according to temperature state

---

## 📊 Temperature History Chart

Built using **Chart.js**

Includes:

- Live updating graph
- Last 30 temperature readings
- Safe temperature zone highlighting
- Automatic trend detection
- Color changes based on temperature status

---

## 🚨 Smart Alert System

When temperature exceeds safe limits:

- Flashing background
- Animated warning banner
- Audio alarm
- Critical AI recommendations
- Automatic status updates

---

## 📅 Vaccine Lifecycle Tracking

Displays:

- Batch ID
- Manufacturing Date
- Expiry Date
- Remaining Days
- Expiry Progress Bar

---

## 📈 Dashboard Statistics

The dashboard continuously displays:

- Minimum Temperature
- Maximum Temperature
- Average Temperature
- Total Alerts Triggered

---

## 🌌 Animated User Interface

Modern futuristic interface including:

- Animated starfield background
- Glassmorphism cards
- Neon effects
- Smooth animations
- Responsive design
- Orbitron typography

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| HTML5 | Page Structure |
| CSS3 | Styling & Animations |
| JavaScript (ES6) | Application Logic |
| Three.js | 3D Visualization |
| Chart.js | Temperature Charts |
| Blynk Cloud API | IoT Sensor Data |
| Google Fonts | Typography |

---

# 📂 Project Structure

```
VaxSafe-AI/
│
├── index.html
├── README.md
└── assets/
    ├── images/
    ├── icons/
    └── screenshots/
```

---

# ⚙️ How It Works

### Step 1

The dashboard connects to the **Blynk Cloud API** using the provided authentication token.

↓

### Step 2

Every 5 seconds the latest temperature value is fetched.

↓

### Step 3

The AI engine analyzes the temperature.

↓

### Step 4

The system classifies the condition into:

- ✅ Safe
- ⚠️ Warning
- 🚨 Critical

↓

### Step 5

The dashboard updates:

- Temperature display
- Gauge
- AI recommendation
- 3D model
- Temperature chart
- Statistics

↓

### Step 6

If the temperature becomes critical:

- Alarm starts
- Banner appears
- Background flashes
- AI recommends emergency actions

---

# 🌡️ Temperature Classification

| Temperature | Status |
|------------|---------|
| -2°C to +8°C | ✅ Safe |
| -6°C to -2°C | ⚠️ Warning |
| +8°C to +14°C | ⚠️ Warning |
| Below -6°C | 🚨 Critical |
| Above +14°C | 🚨 Critical |

---

# 🔗 Blynk Integration

The dashboard retrieves sensor values using:

```
https://blynk.cloud/external/api/get?token=YOUR_BLYNK_TOKEN&V0
```

Simply replace the authentication token with your own Blynk Cloud token to connect to your IoT device.

---

# 🚀 Installation

## Clone the repository

```bash
git clone https://github.com/yourusername/VaxSafe-AI.git
```

---

## Open the project

Open the project folder in **Visual Studio Code**.

---

## Run

Simply open:

```
index.html
```

in your preferred web browser.

No additional installation is required.

---

# 📸 Screenshots

You can add screenshots here.

Example:

```
assets/screenshots/dashboard.png

assets/screenshots/chart.png

assets/screenshots/3d-model.png

assets/screenshots/alerts.png
```

---

# 🔮 Future Improvements

- Firebase Database Integration
- User Authentication
- Historical Report Generation
- PDF Export
- Email Alerts
- SMS Notifications
- Blockchain-based Vaccine Tracking
- AI Predictive Analytics
- ESP32 Integration
- Multiple Sensor Support
- GPS Tracking
- Mobile Application
- Cloud Dashboard

---

# 💡 Learning Outcomes

This project demonstrates practical implementation of:

- HTML5
- CSS3
- JavaScript
- API Integration
- Three.js
- Chart.js
- IoT Dashboard Development
- Data Visualization
- Responsive Web Design
- AI-based Decision Logic
- Cold Chain Monitoring

---

# 🎓 Academic Use

This project was developed as part of a learning project to understand:

- IoT Dashboard Design
- Cold Chain Monitoring
- Healthcare Technology
- Web Development
- Data Visualization
- AI-assisted Monitoring Systems

---

# 👨‍💻 Author

**Yatharth Jain**

**Computer Science Student**

**Software Developer | Web Developer**

GitHub: https://github.com/yourusername

LinkedIn: https://www.linkedin.com/in/yatharthjain1234879

---

# 📄 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute this project for educational and personal purposes.
