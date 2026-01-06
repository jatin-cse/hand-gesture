# Hand Gesture Finger Counter (Python)

This is a real-time **Hand Gesture Recognition** project built using **Python**, **OpenCV**, and **MediaPipe**.  
The program uses a webcam to detect a hand and accurately counts the number of fingers shown.  
It works correctly for **both left and right hands**.

---

## 🔹 Features
- Real-time hand detection using webcam  
- Finger counting (0–5)  
- Supports left and right hands  
- Beginner-friendly and clean code  
- Good project for Python & Computer Vision beginners  

---

## 🔹 Technologies Used
- Python 3.10 / 3.11  
- OpenCV  
- MediaPipe  

---

## 🔹 Project Structure
```text
hand-gesture/
├── hand.py
├──hand_gesture.py
├── camera.py
└── README.md
---
``` 
## 🔹 Installation
Make sure Python **3.10 or 3.11** is installed (do not use Python 3.14).

Install required libraries:
```bash
py -3.11 -m pip install opencv-python mediapipe numpy
``` 
## 🔹 How to Run

1. Open **Command Prompt**
2. Go to the project folder:
```bash
cd path/to/hand-gesture
```
3. Run the program:
```bash
py -3.11 hand_gesture.py
```
4. Press Q to exit the camera window.
##🔹 Supported Gestures

| Gesture       | Result |
| ------------- | ------ |
| ✊ Fist        | 0      |
| ☝ One finger  | 1      |
| ✌ Two fingers | 2      |
| 🖐 Open hand  | 5      |
##🔹 Learning Outcomes
-Basics of computer vision
-Hand landmark detection
-Finger counting logic
-Real-time webcam processing
##🔹 Future Scope
-Gesture-based volume control
-Rock Paper Scissors game
-Gesture-controlled mouse
##Author
Jatin
⭐ Star the repository if you like the project!
