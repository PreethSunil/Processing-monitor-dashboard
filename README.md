# 🖥️ SYS_MONITOR_v1 – Real-Time Process Monitoring Dashboard

## 📌 Overview

**SYS_MONITOR_v1** is a visually immersive, web-based system monitoring dashboard designed to simulate real-time process tracking, system diagnostics, and administrative control actions.

It provides an interactive UI inspired by terminal systems and cybersecurity dashboards, allowing users to visualize CPU usage, memory consumption, and process anomalies while performing simulated management operations.

---

## 🚀 Features

### 🔹 Real-Time Metrics

* Displays CPU usage and memory consumption dynamically
* Simulates real-time system telemetry updates
* Visual feedback through animated UI elements

### 🔹 Process Management

* Terminate high CPU processes
* Suspend memory-heavy processes
* Restart stalled or zombie processes

### 🔹 Issue Detection

* Detects simulated anomalies such as:

  * High CPU usage
  * Memory overflow
  * Stalled processes
* Logs alerts in a terminal-style interface

### 🔹 Interactive Dashboard UI

* Glassmorphism + cyberpunk theme
* Animated radial pulse background
* Scroll-based parallax interface
* Terminal log streaming system

---

## 🧠 How It Works

The system is divided into three main components:

### 1. Control Panel

* Allows admin actions like terminate, suspend, restart
* Updates system metrics dynamically

### 2. Forensic Panel

* Displays detailed process diagnostics
* Shows anomaly detection and actions taken

### 3. Terminal Log

* Logs system events in real-time
* Displays alerts and resolution messages

---

## 🛠️ Technologies Used

* HTML5 – Structure
* CSS3 – Styling, animations, glass UI
* JavaScript (Vanilla) – Logic and interactivity
* Custom Fonts:

  * Surgena (UI)
  * JetBrains Mono (Terminal)

---

## 📂 Project Structure

```
SYS_MONITOR_v1/
│
├── index.html       # Main dashboard file
├── README.md        # Project documentation
```

---

## ⚙️ Installation & Usage

1. Download or clone the repository:

```
git clone https://github.com/your-username/sys_monitor_v1.git
```

2. Open the project folder

3. Run the project:

* Simply open `index.html` in your browser
* OR use VS Code Live Server for better experience

---

## 🎮 How to Use

1. Click **START MONITOR**
2. Scroll to access the dashboard
3. Use control buttons:

   * TERM: HIGH_CPU_PROC
   * SUSP: MEMORY_HOG
   * REST: STALLED_PROC
4. Watch:

   * Logs update in terminal
   * Metrics change dynamically
   * System status toggles between *STABLE* and *ACTION REQUIRED*

---

## 🎨 UI Highlights

* Fully responsive layout
* Animated background using CSS variables
* Smooth scroll and parallax effects
* Terminal-inspired logging system

---

## ⚠️ Note

This project is a **simulation** and does not interact with real system processes. It is intended for:

* Learning UI/UX design
* Understanding system monitoring concepts
* Demonstrating frontend engineering skills

---

## 🔮 Future Enhancements

* Connect with real backend (Node.js / Python)
* Integrate actual system metrics using APIs
* Add authentication system
* WebSocket-based real-time updates
* Deploy as a full-stack monitoring tool

---

## 👨‍💻 Author

**Preeth Sunil**
BTech CSE Student
