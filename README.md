# 🚗 Driver Drowsiness Detection System

A computer vision-based driver monitoring system that detects driver drowsiness and provides alert warnings for safety.

---

## 📌 Overview
This project is a real-time driver monitoring system designed to detect drowsiness using computer vision techniques. It analyzes the driver's eye movements through a webcam and triggers an alert sound when signs of drowsiness are detected.

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
- Pygame  
- MediaPipe  

---

## 📂 Project Files
- `driver_monitoring.ipynb` → Main implementation  
- `horn.mp3` → Alert sound  
- `warning.mp3` → Warning sound  

---

## ⚙️ How It Works
1. Captures video from webcam  
2. Detects face and eyes using computer vision  
3. Monitors eye closure duration  
4. If eyes remain closed beyond a threshold → triggers alert sound  

---

## ▶️ How to Run

1. Install dependencies:
```bash
pip install opencv-python numpy pygame mediapipe
```
2. Run the notebook:
```bash
jupyter notebook driver_monitoring.ipynb
```
3. Execute all cells to start detection

---

## 📈 Output
- Detects drowsiness in real time
- Plays alert sound when driver is sleepy

---

## 🎥 Project Demo
👉 [Click here to watch the demo](https://drive.google.com/file/d/1qhaI66TEVhs5QXnBnIwNB3LtJJj6PSk-/view?usp=sharing)

---

## 🎯 Future Improvements
- Add deep learning-based detection (CNN)
- Improve accuracy in low-light conditions
- Convert into mobile or web application

---

## 👩‍💻 Author
**Ridhima Bais**
