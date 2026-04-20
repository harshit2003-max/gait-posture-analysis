# 🧍‍♂️ Gait Detection & Human Posture Analysis (CNN + IoT)

## 📌 Overview
This project presents a real-time posture and gait analysis system using Computer Vision, Deep Learning, and IoT. It detects human posture and provides instant feedback using an ESP32-based vibration system.

## 🚀 Features
- Real-time posture detection using OpenCV & MediaPipe
- 1D CNN model for classification
- 4 posture classes:
  - Good Sitting
  - Bad Sitting
  - Good Standing
  - Bad Standing
- ESP32-based haptic feedback system
- Lightweight & cost-effective solution

## 🛠️ Tech Stack
Python, OpenCV, MediaPipe, TensorFlow, ESP32, NumPy, Pandas

## 🧪 Methodology
- Extracted 33 body landmarks using MediaPipe
- Built 1D CNN model on (33,3) input tensor
- Classified posture into 4 categories
- Integrated IoT feedback using ESP32

## 📊 Results
- Achieved ~90% accuracy
- Works in real-time using webcam

## ⚡ Pipeline
Camera → MediaPipe → Keypoints → CNN → Prediction → ESP32 Feedback

## 📁 Project Structure
