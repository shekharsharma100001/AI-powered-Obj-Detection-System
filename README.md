# AI-powered-Obj-Detection-System
This repo Consist of AI-powered Object detection system for space station environment


# YOLOv8 Detection App

This is a simple Streamlit web application for real-time object detection using the YOLOv8 model. It supports both **webcam streaming** and **video file uploads** for detecting objects.

---

## 🚀 Features

- **Webcam Mode**: Live object detection from your webcam.
- **Upload Mode**: Upload a video file (mp4, avi, mov, mkv) for batch processing.
- **Confidence Threshold**: Adjustable slider to control detection confidence.
- Built on [Ultralytics YOLOv8](https://docs.ultralytics.com/), Streamlit, and OpenCV.

---

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

Make sure you have Python 3.7 or later.

---

## 🛠️ Usage

1. Place your YOLOv8 model weights as `best.pt` in the same directory as `app.py`.
2. Run the app:

```bash
streamlit run app.py
```

3. Select **Webcam** or **Upload Video** mode from the sidebar.
4. Adjust the confidence threshold as needed.

---

## 📁 File Structure

```
.
├── app.py
├── best.pt           # Your trained YOLOv8 model
├── requirements.txt
└── README.md
```

---

## 📌 Notes

- The app uses `ultralytics.YOLO` for inference. Make sure `best.pt` is compatible with YOLOv8.
- Streamlit WebRTC may require webcam permissions in your browser.
- Tested on Google Chrome and Firefox.

---

## 🧠 Author

Made with ❤️ using Streamlit and YOLOv8.

---



