# 🚗 Crash Detection System (YOLOv8 + ESP32-CAM)

## 📌 Project Description
This project detects road crashes in real-time using YOLOv8 object detection. The ESP32-CAM module provides live video streaming, and the AI model detects accident-like scenarios.

## ✨ Features
- Real-time crash detection
- ESP32-CAM live stream support
- Tkinter UI for video source selection
- Bounding boxes for accident detection

## ⚙️ Requirements
- Python 3.8+
- ultralytics (YOLOv8)
- opencv-python
- pandas
- cvzone
- tkinter

## 🚀 Usage
1. Clone the repository
1. Install dependencies using `pip install -r requirements.txt`
1. Run `python crash_detection.py`
1. Select a video file or use ESP32-CAM live feed
1. Detected crashes will be highlighted in red

