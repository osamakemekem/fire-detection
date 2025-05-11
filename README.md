# 🔥 Fire Detection System using YOLOv8 & Computer Vision

This project detects fire in **images**, **videos**, and **real-time camera feeds** using a trained YOLOv8 model. It also sends real-time alerts via **Telegram** when fire is detected.

---

## 📚 Project Overview

Fire detection is critical for preventing loss of life and property. This project uses artificial intelligence and computer vision to automate fire recognition across different types of media:

* 🖼️ Static Images
* 🎞️ Pre-recorded Videos
* 📹 Real-time Camera Feeds

When fire is detected, the system highlights it and sends an immediate Telegram alert.

---

## ⚙️ Project Structure

```
Fire_Detection/
│
├── IMAGE_DONE.py              # Detect fire in a single image
├── VIDEO_DONEE.py             # Detect fire in a video file
├── Real_Time_DONE.py           # Detect fire from webcam or CCTV feed
├── best.pt                    # Trained YOLOv8 model weights
├── requirements.txt           # Required libraries
├── dataset.zip                # Dataset used for the model
└── README.md                  # Project documentation (this file)
```

---

## 🚀 How Each Script Works

### `IMAGE_DONE.py`

* Loads an image from a specified path
* Uses YOLOv8 to detect fire
* If detected, draws bounding boxes and sends a Telegram alert

### `VIDEO_DONE.py`

* Loads a video file
* Processes it frame-by-frame
* Detects fire, draws bounding boxes, and alerts if fire is found

### `REALTIME_DONE.py`

* Connects to a live camera stream
* Detects fire in real-time
* Sends instant Telegram alerts with frames showing the fire

---

## 🛠️ Requirements

* Python 3.8+
* Ultralytics (YOLOv8)
* OpenCV
* Requests

Install all dependencies using:

```bash
pip install -r requirements.txt
```

### `requirements.txt`

```txt
ultralytics
opencv-python
requests
```

---

## 🖼️ Sample Output

* 🔲 Fire zones are highlighted with bounding boxes
* 📤 Fire alerts are sent to your Telegram account
* ✅ Real-time and batch processing supported

---

## ✨ Future Improvements

* Add web-based dashboard for alert monitoring
* Enable GPS and timestamp logging
* Improve detection accuracy in low light or foggy conditions
* Add support for mobile camera input

---

## 🤝 Contribution

Feel free to fork this repo, suggest improvements, or contribute code!
If this project helps you, please ⭐ it.

---

## 📩 Contact

Developed by:

* [Yasmeen](https://github.com/yasmeenn88)
* [Osama Kemekem](https://github.com/osamakemekem)
* [NufalXBaalash](https://github.com/NufalXBaalash)

For questions or collaboration, feel free to reach out on GitHub.
