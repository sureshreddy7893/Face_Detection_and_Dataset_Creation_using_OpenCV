# Face_Detection_and_Tracking
## 📌 Project Overview
This project implements a real-time face detection system using OpenCV and Haar Cascade classifiers. It detects human faces through a webcam and captures face images to create a structured dataset for future computer vision and face recognition tasks.

The project is divided into two logical modules:
1. Face Detection
2. Dataset Creation

---

## 🛠️ Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier
- Computer Vision

---

## 📂 Project Structure
Face_Detection_and_Tracking/
1. dataset/images
2. haarcascade_frontalface_default.xml
3. face_detection.py
4. dataset_creation.py
5. Screenshots
6. README.md
7. requirements.txt
8. Screenshots

---

## ⚙️ Project Modules

### 1️⃣ Face Detection Module
- Detects faces in real time using a webcam
- Converts frames to grayscale for better accuracy
- Uses Haar Cascade frontal face classifier
- Draws bounding boxes around detected faces

**File:** `face_detection.py

---

### 2️⃣ Dataset Creation Module
- Detects faces from live webcam feed
- Extracts face region (ROI)
- Resizes images to fixed dimensions
- Stores face images in a structured dataset folder

**File:** `dataset_creation.py`

---
## 🚀 How to Run the Project

1. Install Dependencies
: pip install -r requirements.txt

2. Run Face Detection
  : python face_detection.py

3. Create Face Dataset
  : python dataset_creation.py
   
5. Press ESC to exit the webcam window.

---

🧠 Learning Outcomes

Practical understanding of Haar Cascade face detection

Real-time image processing using OpenCV

Dataset generation for machine learning pipelines

Parameter tuning for detection accuracy and performance

---

🔮 Future Enhancements

Integrate face recognition (LBPH / Deep Learning)

Improve detection under different lighting conditions

Build attendance or authentication systems

---

⚠️ Disclaimer

This project is developed for educational purposes only. Face images are not included in the repository to ensure user privacy.

Note: Dataset images are intentionally excluded and maintained in a private repository to ensure data privacy and ethical use.

---

👨‍💻 Author

Suresh Reddy Munagala

---
