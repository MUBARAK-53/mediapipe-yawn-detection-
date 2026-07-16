# mediapipe-yawn-detection-

# 😴 Real-Time Yawn Detection using MediaPipe

A real-time Computer Vision project that detects yawning using facial landmarks extracted by MediaPipe and the Mouth Aspect Ratio (MAR).

---

## Features

- Real-time Face Landmark Detection
- Mouth Aspect Ratio (MAR)
- Mouth Open / Closed Detection
- Consecutive Frame Analysis
- Yawn Detection
- Yawn Counter
- Webcam Support
- Video Support

---

## Tech Stack

- Python
- OpenCV
- MediaPipe
- Math

---

## Mouth Landmarks

| Landmark | Purpose |
|----------|---------|
|61|Left Corner|
|13|Upper Lip|
|82|Upper Inner Lip|
|291|Right Corner|
|317|Lower Inner Lip|
|14|Lower Lip|

---

## MAR Formula

MAR = (A + B) / (2 × C)

Where

- A = Upper Lip ↔ Lower Lip
- B = Inner Upper Lip ↔ Inner Lower Lip
- C = Left Corner ↔ Right Corner

---

## Output

- Displays Mouth Aspect Ratio
- Detects Mouth Open/Closed
- Detects Yawning
- Counts Total Yawns

---


## 📸 Results

### Input

![Input](Images/input.png)

### Output

![Output](Images/output.png)

## Future Improvements

- Driver Drowsiness Detection
- EAR + MAR Fusion
- Head Pose Estimation
- Fatigue Monitoring
- YOLO Integration

---


## Author

Mubarak Naikwade
