# 🕳 PotholeKoi? — AI-Based Pothole Detection System

Are There Pothole? is a modern web-based pothole detection application that allows users to upload road images or capture them live using a camera to detect potholes using AI models.

The platform provides **side-by-side visual comparison** between two object detection models:

* **YOLOv8-seg** → Instance Segmentation
* **YOLOv26** → Bounding Box Detection

Built with a futuristic UI and real-time simulation pipeline for easy demonstration and model comparison.

---

## 🚀 Features

* ✅ Upload road images for pothole analysis
* ✅ Capture live road images using device camera
* ✅ Side-by-side model comparison
* ✅ YOLOv8 segmentation mask visualization
* ✅ YOLOv26 bounding box detection visualization
* ✅ Detection confidence scoring
* ✅ Responsive futuristic UI
* ✅ Drag-and-drop image upload
* ✅ Real-time processing animations

---

## 🛠 Tech Stack

### Frontend

* HTML5
* CSS3
* Vanilla JavaScript

### AI Models

* YOLOv8-seg
* YOLOv26

### Backend (Planned / Production)

* Python
* Flask / FastAPI
* OpenCV
* Ultralytics YOLO

---

## 📂 Project Structure

```bash
PotholeKoi/
│── pothole_detection.html   # Main frontend application
│── assets/                  # Images / Icons (optional)
│── backend/                 # Python backend (future integration)
│── models/                  # YOLO model weights
│── README.md
```

---

## ⚡ How It Works

1. Upload an image or capture from camera.
2. The image is processed through:

   * **YOLOv8-seg** for segmentation masks.
   * **YOLOv26** for object detection boxes.
3. Results are displayed side-by-side.
4. Detection statistics are shown:

   * Number of potholes
   * Confidence score
   * Model comparison

---

## 🎯 Current Status

Currently, the system uses **simulated detections** on the frontend for demonstration purposes.

In production, you can replace the simulation with actual backend APIs:

```javascript
fetch('/detect-yolov8', { method: 'POST' })
fetch('/detect-yolov26', { method: 'POST' })
```

---

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/PotholeKoi.git
cd PotholeKoi
```

Run locally:

```bash
open pothole_detection.html
```

Or use Live Server in VS Code.

---


## 📸 Output Screenshots

* YOLOv8-seg Result
![Alt text](out0.png?raw=true "Optional Title")
* YOLOv26 Result
![Alt text](out2.png?raw=true "Optional Title")


---
## 🔴Live Output
* https://huggingface.co/spaces/iam-ahadulislam/AreTherePothole

## 👨‍💻 Authors

Developed by:

* **Ahadul Islam Rahul**


## 🌍 Vision

To build smarter roads by using AI-powered detection systems that help identify and report potholes quickly, reducing accidents and improving transportation infrastructure.
