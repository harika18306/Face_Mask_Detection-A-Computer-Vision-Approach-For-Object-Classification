# Face Mask Detection

A real-time Face Mask Detection system built using OpenCV, TensorFlow, and Keras.
The model detects whether a person is wearing a mask from images and live webcam video.

---

## 🚀 Features

* Detect mask in static images
* Real-time webcam detection
* Streamlit web application
* Lightweight and fast (MobileNetV2)

---

## 🧰 Tech Stack

* Python
* OpenCV
* TensorFlow / Keras
* Streamlit
* MobileNetV2

---

## 📂 Project Structure

```
Face-Mask-Detection/
│
├── app.py
├── detect_mask_image.py
├── detect_mask_video.py
├── mask_detector.model
├── face_detector/
├── requirements.txt
└── images/
```

---

## ⚙️ Installation

1. Clone the repository

```
git clone <repo-url>
cd Face-Mask-Detection
```

2. Create and activate virtual environment (Python 3.10 recommended)

```
python -m venv env
env\Scripts\activate
```

3. Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Usage

### 🔹 Detect mask in an image

```
python detect_mask_image.py --image images/test.jpg
```

### 🔹 Real-time webcam detection

```
python detect_mask_video.py
```

Press **q** to stop the webcam.

### 🔹 Run Streamlit web app

```
streamlit run app.py
```

---

## 📊 Model

* Base Model: MobileNetV2
* Framework: TensorFlow/Keras
* Task: Binary Classification (Mask / No Mask)

---

