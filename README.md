# 🚌 UTHM Pagoh Shuttle Bus Tracker

![Version](https://img.shields.io/badge/version-1.0.1-blue.svg)
![Vue.js](https://img.shields.io/badge/Vue.js-3.x-4FC08D.svg?logo=vue.js)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC.svg?logo=tailwind-css)

A lightweight, real-time web dashboard designed for students at **Universiti Tun Hussein Onn Malaysia (UTHM) Pagoh Campus**. It helps students track shuttle bus schedules between *Kolej Kediaman Pagoh* and *Kampus Pagoh* without the guesswork.

## 😤 The Problem
UTHM Pagoh students often face the daily struggle of missing the bus or waiting blindly at the terminal or cafe parking lot under the hot sun. Memorizing the static, complex schedule (especially with Friday prayer variations) is frustrating and inefficient.

## 💡 The Solution
This web app brings the static schedule to life! By matching the user's real-time device clock with the official bus schedule, it provides a live, dynamic dashboard showing exactly when the next bus departs and which buses are currently on the road.

## ✨ Features
*   **Live Countdown:** See exactly how many minutes are left until the next bus departs.
*   **Active Route Tracking:** Visual indicators show which buses are currently moving and estimates their arrival.
*   **Smart Scheduling:** Automatically switches between "Isnin - Khamis" and "Jumaat" schedules based on the current day.
*   **Solat Jumaat Integration:** Highlights special Friday prayer trips to Masjid Hj Muhammad Yassin.
*   **Weekend Alerts:** Automatically notifies users when buses are not operating.
*   **Time Simulator:** A built-in sandbox mode to test schedules by manually overriding the time and day.

## 🛠️ Tech Stack
This project is built to be fast, responsive, and completely serverless:
*   **HTML5**
*   **Vue.js 3 (via CDN):** Handles the reactive countdowns and time-logic.
*   **Tailwind CSS (via CDN):** For a sleek, modern, and mobile-first dark mode UI.
*   **FontAwesome:** For intuitive icons.

## 🚀 How to Use (Local Setup)
Because this app relies entirely on frontend technologies via CDNs, there are no heavy `node_modules` to install!
1. Clone this repository to your local machine.
2. Open `index.html` directly in any modern web browser.
3. Done!

---
*Built with ❤️ for UTHM Pagoh Students.*