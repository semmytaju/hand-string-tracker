

# 🖐️ Hand String Tracker

A real-time, interactive web application that tracks hand movements using your webcam and visualizes colorful "strings" connecting your fingers. When two hands are detected, dynamic threads connect corresponding fingers between them, creating a smooth, magical visual effect.

Built with **HTML5**, **CSS3**, **JavaScript**, and **MediaPipe Hands**.

<img src="/demo.png" width="800">

## ✨ Features

- **🎯 Real-Time Tracking**: Accurate hand landmark detection using Google's MediaPipe AI.
- **🧵 Dynamic Strings**: 
  - **Single Hand**: Colorful strings connect joints within each finger.
  - **Two Hands**: Elastic-like threads connect corresponding fingers between both hands.
- **🎨 Finger-Specific Colors**:
  - 🔴 Thumb: Coral Red
  - 💠 Index: Turquoise
  - 🔵 Middle: Sky Blue
  - 🟢 Ring: Mint Green
  - 🟡 Pinky: Pastel Yellow
- **✨ Smooth Visuals**: Gradient lines, glow effects, and 3D shadows for a realistic look.
- **🪞 Mirror Mode**: Natural mirror reflection for intuitive interaction.
- **📱 Full Screen**: Immersive full-screen experience with a floating glassmorphism UI.
- **🚀 No Installation Required**: Runs directly in the browser (Chrome/Firefox/Edge).

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **AI/ML**: [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
- **Camera Access**: WebRTC / MediaDevices API

## 📥 How to Install & Run Locally

   ```bash
   git clone https://github.com/semmytaju/hand-string-tracker.git
   cd hand-string-tracker
