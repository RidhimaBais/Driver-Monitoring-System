# Driver-Monitoring-System
A computer vision-based driver monitoring system that detects driver drowsiness and provides alert warnings for safety.

# 🚗 Driver Drowsiness Detection System

## 📌 Overview
This project is a real-time driver monitoring system designed to detect drowsiness using computer vision techniques. 
It analyzes the driver's eye movements through a webcam and triggers an alert sound when signs of drowsiness are detected.

---

## 🚀 Features
- Real-time face and eye detection
- Drowsiness detection based on eye closure
- Audio alert system (warning & horn sound)
- Simple and efficient implementation using Python

---

## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy
- Jupyter Notebook

---

## 📂 Project Files
- driver_monitoring.ipynb → main implementation
- horn.mp3 → alert sound
- warning.mp3 → warning sound

---

## ⚙️ How It Works
1. Captures video from webcam
2. Detects face and eyes using OpenCV
3. Monitors eye closure duration
4. If eyes remain closed beyond a threshold → triggers alert sound

---

## ▶️ How to Run
1. Install dependencies:
  pip install opencv-python numpy
2. Run the notebook:
  jupyter notebook driver_monitoring.ipynb

3. Execute all cells to start detection

---

## 📈 Output
- Detects drowsiness in real time
- Plays alert sound when driver is sleepy

---

## 🎯 Future Improvements
- Add deep learning-based detection (CNN)
- Improve accuracy in low light conditions
- Convert into mobile or web application

---

## 👩‍💻 Author
Ridhima Bais
