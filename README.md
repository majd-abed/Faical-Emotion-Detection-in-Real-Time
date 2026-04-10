[README.md](https://github.com/user-attachments/files/26624958/README.md)
# 🎭 Facial Emotion Detection in Real-Time

A real-time facial emotion recognition system that detects and
classifies human emotions from live video using computer vision and deep
learning techniques.

------------------------------------------------------------------------

## 📌 Overview

This project captures live video from a webcam, detects faces, and
predicts the emotional state of each detected face in real-time. It is
built using modern computer vision libraries and pre-trained deep
learning models.

The system identifies emotions such as:

-   😊 Happy\
-   😢 Sad\
-   😠 Angry\
-   😮 Surprise\
-   😐 Neutral\
-   😨 Fear\
-   🤢 Disgust

Real-time emotion detection has applications in **human-computer
interaction, healthcare, education, and smart surveillance systems**.

------------------------------------------------------------------------

## 🚀 Features

-   🎥 Real-time webcam face detection\
-   🧠 Emotion classification using deep learning\
-   📦 Lightweight and easy to run\
-   📊 Live emotion labels displayed on video frames\
-   ⚡ Fast processing (hardware dependent)\
-   🧩 Modular and easy to extend

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   **Python**
-   **OpenCV**
-   **TensorFlow / Keras / Deep Learning model**
-   **NumPy**

------------------------------------------------------------------------

## 📂 Project Structure

    Facial-Emotion-Detection-in-Real-Time/
    │
    ├── emotion_detection.py
    ├── model/
    ├── utils/
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## ⚙️ Installation

### 1. Clone the repository

``` bash
git clone https://github.com/majd-abed/Faical-Emotion-Detection-in-Real-Time.git
cd Faical-Emotion-Detection-in-Real-Time
```

### 2. Create a virtual environment

``` bash
python -m venv venv
source venv/bin/activate
venv\Scripts\activate
```

### 3. Install dependencies

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

## ▶️ Usage

``` bash
python emotion_detection.py
```

Press **q** to quit.

------------------------------------------------------------------------

## 🧠 How It Works

1.  Capture video frames\
2.  Detect faces\
3.  Preprocess input\
4.  Predict emotion\
5.  Display results

------------------------------------------------------------------------

## ⚠️ Limitations

-   Sensitive to lighting\
-   Best with frontal faces\
-   Model accuracy varies

------------------------------------------------------------------------
