# 🪖 Ride Guardian Smart Helmet
### A Multidisciplinary Solution for Safer and Healthier Urban Riding

**Ride Guardian Control Centre** is a web-based, software-only prototype developed as part of a Multidisciplinary Project at **VIT Chennai**. It demonstrates how a smart helmet system could monitor riding conditions, generate alerts, and provide audio navigation through an interactive dashboard.

🌐 **Live Website:** https://thelrvikash.github.io/Ride-guardian-Helmet/

---

## 📌 Project Overview

Road safety is an important concern for two-wheeler riders. Distraction, nearby vehicles, environmental conditions, and delayed hazard awareness can make riding more challenging.

Ride Guardian explores how smart helmet technologies could help address these challenges. Since hardware integration is not available for this prototype, the project uses simulated sensor readings and browser-based interactions to demonstrate the proposed features.

## 🎯 Objectives

- Explore the role of smart technology in improving rider awareness.
- Demonstrate sensor-based monitoring through simulated inputs.
- Display alerts for potentially unsafe riding and environmental conditions.
- Demonstrate audio navigation using browser text-to-speech.
- Present the proposed smart helmet features through a responsive web dashboard.

## ✨ Features

### 1. 📊 Interactive Control Centre
- Displays an overall system status.
- Shows the number of active warnings and session events.
- Updates the dashboard when simulated readings change.

### 2. 📡 Simulated Sensor Monitoring
The dashboard includes controls for the following sensor concepts:

| Parameter | Proposed Sensor / Concept |
|---|---|
| Vehicle speed | GPS / speed sensor |
| Object distance | Ultrasonic sensor |
| Temperature and humidity | DHT11 / DHT22 |
| Ambient light | BH1750 |
| Air / gas index | MQ sensor |
| Motion / impact level | MPU6050 |
| Noise level | Microphone |
| Blind-spot status | IR / radar concept |
| Helmet-worn status | Wear-detection concept |

### 3. ⚠️ Warning and Alert System
The prototype uses illustrative, rule-based thresholds to demonstrate warnings for conditions such as:
- High vehicle speed
- Nearby objects
- High temperature
- Low ambient light
- Elevated air/gas index
- High noise levels
- Increased motion/impact readings
- Simulated blind-spot and navigation hazards

These alerts demonstrate the intended logic and are not validated safety warnings.

### 4. 🔊 Audio Navigation
- Uses the browser's text-to-speech capability, when supported.
- Provides sample navigation instructions.
- Allows users to speak, advance, and stop instructions.

### 5. 🎥 Simulated Camera Event
A manual event trigger adds a simulated camera-related event to the session. It does not capture or store actual video.

### 6. 🌡️ Ventilation and Air Filtration Concepts
The dashboard demonstrates the intended response of ventilation and filtration features based on simulated readings.

### 7. 📝 Session Event Log
- Records events during the current browser session.
- Allows users to clear the event log.
- Supports exporting the session log as a CSV file.

### 8. 🎲 Demo Controls
- Generate random demo readings.
- Adjust sensor values manually.
- Reset the session to explore different scenarios.

## 🛠️ Technologies Used

- **HTML** — webpage structure
- **CSS** — styling and responsive dashboard layout
- **JavaScript** — simulated sensor logic, alerts, and interactive controls
- **Web Speech API** — browser-based text-to-speech, where supported
- **CSV export** — saving the session event log
- **GitHub Pages** — hosting the website

## 🚀 How to Use

1. Open the [Ride Guardian Control Centre](https://thelrvikash.github.io/Ride-guardian-Helmet/).
2. Adjust the simulated sensor readings using the available controls.
3. Observe how the warning feed and system status respond.
4. Use **Generate demo readings** to create a sample scenario.
5. Explore the navigation section using the speech controls.
6. Trigger a simulated camera event to view event logging.
7. Export the session log as a CSV file if required.
8. Use **Reset session** to restart the demonstration.

## 🧪 Project Implementation

The current prototype demonstrates the software logic and user interface independently of physical hardware. It uses manually controlled or generated values to simulate the behaviour of the proposed system.

The project provides a foundation for exploring how sensor inputs, rule-based alerts, audio instructions, and event logging could be combined in a future hardware-integrated smart helmet.

## ⚠️ Limitations and Safety Disclaimer

**This project is a demonstration prototype, not a real-world safety system.**

- All sensor readings and detection statuses are simulated.
- The website does not connect to physical sensors or helmet hardware.
- It does not use live GPS, real-time maps, or live route detection.
- It does not perform actual blind-spot or accident detection.
- The camera event trigger does not record video.
- Ventilation and filtration responses are visual demonstrations only.
- Alert thresholds are illustrative and have not been validated for real-world riding.

**Do not rely on this prototype for riding decisions or emergency situations.**

## 🔮 Future Scope

Possible future improvements include:

- Integration with physical sensors and embedded controllers.
- Real GPS-based navigation and route guidance.
- Hardware-based obstacle and blind-spot detection.
- Camera integration for actual event recording.
- Real-time temperature and air-quality monitoring.
- Physical ventilation and filtration control.
- Testing and validation of the system under appropriate conditions.

## 👥 Project Team

**Institution:** VIT Chennai  
**Project:** Multidisciplinary Project (MDP) — Review 2

| Team Member | Registration Number |
|---|---|
| L R VIKASH | 26BCE1155 |
| MITTUN MANIGANDAN N H | 26BEL1130 |
| UTKARSHA BELLAD | 26BME1291 |
| NIYA TREESA JOSEPH | 26BCE1156 |
| SAMPRITI SEN | 26BCE5308 |

## 📄 Project Status

**Current stage:** Software-only simulation prototype

The project demonstrates the proposed control dashboard and software interactions. Physical sensor integration and real-world safety validation are outside the scope of the current version.

---

*Ride Guardian Smart Helmet — Exploring technology for safer and healthier urban riding.*
