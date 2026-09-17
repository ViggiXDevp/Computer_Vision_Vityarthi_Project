# Computer Vision – Vityarthi Project

> A real-time computer vision system built with Python and OpenCV as part of the VITyarthi course.  
> This project demonstrates practical image processing, feature extraction, and AI-based visual understanding using webcam / image inputs.

![Project Demo](assets/demo.gif)  
## Live Sketch Demo

### Some Results


Normal Thresholding

<img src="https://github.com/akshaybhatia10/ComputerVison-Projects/blob/master/LiveSketch/Example-Normal%20Threshold.png" alt="" data-canonical-src="https://github.com/akshaybhatia10/ComputerVison-Projects/blob/master/LiveSketch/Example-Normal%20Threshold.png" width="300" height="300" />


Adaptive Thresholding

<img src="https://github.com/akshaybhatia10/ComputerVison-Projects/blob/master/LiveSketch/Example-Adaptive%20Threshold.png" alt="" data-canonical-src="https://github.com/akshaybhatia10/ComputerVison-Projects/blob/master/LiveSketch/Example-Adaptive%20Threshold.png" width="300" height="300" />


Other Examples

<img src="https://github.com/akshaybhatia10/ComputerVison-Projects/blob/master/LiveSketch/More%20examples.png" alt="" data-canonical-src="https://github.com/akshaybhatia10/ComputerVison-Projects/blob/master/LiveSketch/More%20examples.png" width="300" height="300" />

---

## 📌 Overview

This repository contains the implementation of **VisionGuard**, a computer vision application that:

- Captures live video from a webcam (or processes images/videos).
- Applies computer vision and machine learning techniques to extract meaningful visual information.
- Provides real-time feedback / visualization based on the detected patterns.

The project is developed as part of the **VITyarthi Computer Vision course**, aligning with topics such as image enhancement, transformations, segmentation, feature extraction, and object detection.

---

## ✨ Features

Customize this list to match what you actually implemented. Example:

- **Real-time processing**
  - Live webcam feed with low-latency inference.
  - On-screen visualization of detections (bounding boxes, landmarks, masks, etc.).

- **Core computer vision capabilities** :
  - Face detection and facial landmark extraction.
  - Eye Aspect Ratio (EAR) based blink / drowsiness detection. 
  - Driver distraction detection (e.g., phone usage, yawning, head pose).
  - Salient object detection / background removal using U²-Net or similar architectures. 
  - Image enhancement (noise removal, contrast improvement).
  - Edge detection, contour analysis, shape detection.

- **User-friendly output**
  - Visual overlays (landmarks, contours, masks).
  - Alerts / warnings (e.g., drowsiness alarm, distraction notification).
  - Optional logging of events (blink count, drowsy frames, etc.).

- **Extensible design**
  - Modular code structure for easy experimentation.
  - Configurable thresholds and parameters via constants / config file.

---

## 🛠️ Technologies & Tools Used

- **Language:** Python 3.x
- **Core Libraries:**
  - `opencv-python` (`cv2`) – image/video processing and real-time pipeline 
  - `numpy` – numerical operations on image arrays
  - `dlib` / `mediapipe` – facial landmark detection (if used) 
  - `tensorflow` / `torch` – deep learning models (e.g., U²-Net for background removal)
- **Additional Tools:**
  - `matplotlib` / `seaborn` – optional visualization
- **Development:**
  - Git & GitHub for version control
  - VS Code 

Update this section to exactly match your `requirements.txt` or environment.

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone [https://github.com/ViggiXDevp/Computer_Vision_Vityarthi_Project.git]
cd Computer_Vision_Vityarthi_Project
```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv

# On Windows
venv\Scripts\activate

# On macOS / Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install opencv-python numpy
# pip install dlib mediapipe tensorflow torch
```

> Note: Some libraries (like `dlib`) may require additional system dependencies or a C++ compiler.

---

## 🚀 How to Run

### Basic Usage

For a webcam-based real-time demo:

```bash
python liveSketch.py
```

Expected behavior:

- Your webcam opens in a window.
- The system processes each frame in real time.
- Detected features (faces, eyes, masks, etc.) are drawn on the output window.
- Alerts / counters are updated live (e.g., blink count, drowsiness warning).

---

## 📚 Learning Outcomes

Through this project, key concepts from the VITyarthi Computer Vision course were applied:

- Image acquisition and preprocessing with OpenCV. 
- Feature detection (edges, contours, landmarks).
- Use of geometric features (e.g., EAR) for event detection. 
- Integration of deep learning models for segmentation / classification 
- Building an end-to-end real-time vision pipeline.

---

## 🤝 Contributing

Contributions are welcome! If you’d like to improve the project:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add: your meaningful commit message"
   ```
4. Push and open a pull request.

---

## 📄 License

This project is created as an academic assignment for the VITyarthi Computer Vision course.  
Unless otherwise specified, you can treat it as:

> “For educational and non-commercial use only.”

(Update if you want a specific open-source license like MIT.)

---

## 🙏 Acknowledgements

- VITyarthi platform and mentors for the Computer Vision course.  
- Open-source libraries: OpenCV, dlib, MediaPipe, TensorFlow/PyTorch, etc.
- Reference tutorials and papers on:
  - Eye Aspect Ratio and blink detection 
  - Salient object detection and U²-Net 
  - Driver drowsiness and distraction detection systems 

---

## 📬 Contact

- **Author:** G V VIGHNESH REDDY
- **GitHub:** [@ViggiXDevp](https://github.com/ViggiXDevp)
- **Email:** [gvvighneshreddy8612@gmail.com](gvvighneshreddy8612@gmail.com)

Feel free to reach out for collaborations, feedback, or questions.

