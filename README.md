# 🎭 Real-Time Emotion Detector from Camera Face Input

A deep learning-powered real-time emotion detection system that classifies facial expressions captured from a live webcam feed into seven distinct emotions.

---

## 📌 Project Overview

This application uses a Convolutional Neural Network (CNN) trained on facial expression data to detect and classify human emotions in real-time. The webcam captures a video stream, detects faces, and predicts the emotion being expressed—displaying it with a label overlay.

### 🔍 Detectable Emotions:
- 😠 **Angry**
- 🤢 **Disgust**
- 😨 **Fear**
- 😀 **Happy**
- 😐 **Neutral**
- 😢 **Sad**
- 😲 **Surprise**

---

## 🧠 Features

- ✅ Real-time face detection using OpenCV
- ✅ Emotion prediction using trained CNN model
- ✅ Visual label overlay on detected faces
- ✅ Clean preprocessing pipeline (grayscale, resize, normalize)
- ✅ Customizable and extendable for more use-cases

---

## 🏗️ Model Architecture

- 4 Convolutional Layers (ReLU activation + MaxPooling)
- Dropout layers for regularization
- Fully Connected Dense layers
- Output layer with Softmax (7 classes)

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10 | Core Programming Language |
| TensorFlow / Keras | Deep Learning Framework |
| OpenCV | Real-time Computer Vision |
| NumPy | Numerical Computation |
| Matplotlib | Visualization (optional) |
| Jupyter Notebook | Model Training & Development |

---

## 📦 Dataset

**FER-2013**: Facial Expression Recognition dataset  
🔗 [Kaggle Link](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset)

- 48x48 grayscale images
- 35,900 labeled facial images
- 7 emotion classes

---

## 🚀 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/<your-username>/real-time-emotion-detector.git
cd real-time-emotion-detector

# (Optional) Create a virtual environment
python3 -m venv env
source env/bin/activate  # or .\env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
