# Gesture Control Volume using Hand Tracking

This project demonstrates how to control the volume of your computer using hand gestures detected via a webcam. The system uses hand tracking to identify specific gestures and accordingly adjusts the volume in real-time.

---

## Overview

The project focuses on:
- Detecting and tracking hands using a modular hand tracking module.
- Extracting hand landmarks to interpret gestures.
- Using gestures (e.g., distance between thumb and index finger) to increase or decrease the system volume.

This modular approach simplifies the process by reusing a previously created hand tracking module, making hand detection easy and efficient.

---

## Features

- Real-time hand tracking using OpenCV and MediaPipe.
- Gesture recognition based on hand landmarks.
- Smooth volume adjustment mapped to gesture distance.
- Modular code structure for easy maintenance and upgrades.

---

## Demo

![Gesture Volume Control](demo.gif)

---

## Requirements

- Python 3.x
- OpenCV
- MediaPipe (for hand tracking)
- Pycaw (for Windows volume control) or `osascript` (for macOS), or `amixer` (for Linux)

---
