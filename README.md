# Real-Time Object Detection  
# (Webcam, Image & Video)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-ff4b4b?logo=streamlit&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLO-v8-orange?logo=github)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

This is a object detection app powered by **YOLOv8** and built using **Streamlit**.
This project lets you detect objects in:

* Live webcam feed
* Uploaded images
* Uploaded videos

---

## User Interface

![UI Screenshot](assets/user_interface.png)

---

### 1. Clone the Repository

```bash
git https://github.com/neerajkumarsi20/Object-Detector.git
cd Object-Detector
```

### 2. Setup a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Finally Run the App

```bash
streamlit run app.py
```

To test use the sample image/video within data folder

## Highlighting Features

* Streamlit-powered interactive UI with a clean look and feel.
* Three modes: Webcam, Image, and Video detection.
* Real-time object detection.
* Drag-and-drop image or video uploads.
* Confidence threshold slider to filter predictions.
* Easy to use **(Runs Locally)**
