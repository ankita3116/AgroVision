# 🌱 AgroVision — Crop Disease Detection System

AgroVision is an AI-powered crop disease detection application that uses deep learning to identify diseases from plant leaf images.

## 🚀 Features

- Upload a plant leaf image
- Detect crop diseases using a trained deep learning model
- Display the predicted disease
- Simple and user-friendly Streamlit interface
- TensorFlow Lite model for efficient prediction
- Supports multiple crop disease classes

## 🧠 Technology Stack

- Python 3.11
- TensorFlow 2.17.0
- TensorFlow Lite
- Streamlit
- NumPy
- OpenCV
- Pillow
- Plotly
- Deep Translator

## 📁 Project Structure

```text
AgroVision/
│
├── app/
│   ├── app.py
│   ├── requirements.txt
│   └── style.css
│
├── model/
│   ├── class_names.json
│   └── crop_disease_model.tflite
│
├── notebooks/
│
├── .streamlit/
├── .gitignore
├── .python-version
└── README.md
