# 🎨 AirCanvas — Real-Time Gesture Drawing

AirCanvas is a computer vision-based application that allows users to draw on a virtual canvas in real time using hand gestures captured through a webcam — eliminating the need for traditional input devices like a mouse or stylus.

## 🚀 Features

* ✋ Real-time hand tracking using MediaPipe (21 landmarks)
* 🎨 Gesture-based drawing on virtual canvas
* 🌈 Color switching using hand gestures
* 🖌 Adjustable brush size
* 🧹 Canvas clear and undo functionality
* ⚡ Smooth and low-latency performance

## 🧠 Tech Stack

* Python
* OpenCV
* MediaPipe
* NumPy

## 🎯 How It Works

* Detects hand using MediaPipe Hands
* Tracks fingertip positions
* Maps gestures to drawing actions
* Renders strokes on a virtual canvas using OpenCV

## 📸 Demo

(Add your demo video link here)

## ▶️ Run Locally

```bash
pip install opencv-python mediapipe numpy
python main.py
```
