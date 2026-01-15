# Indian Sign Language Detection Model AI (Real-Time)
A real-time hand sign detection system that uses a live webcam feed to recognize
Indian Sign Language (ISL) gestures using machine learning and computer vision.
This project demonstrates an end-to-end real-time computer vision pipeline,
from model training to live camera-based inference.

## Dataset
- Indian Sign Language Dataset (Kaggle)  
- https://www.kaggle.com/datasets/soumyakushwaha/indian-sign-language-dataset  

Dataset is not included due to size and licensing constraints.

## How It Works
- Train ML models on ISL hand sign data
- Integrate the trained model with a live camera feed
- Perform real-time gesture detection

## Quick Setup
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Download dataset from Kaggle
4. Run `Real Time Detection.ipynb`

## Files
- Models used.ipynb-> Model experiments <br>
- Real Time Detection.ipynb-> Live webcam detection <br>
- app.ipynb-> Application workflow <br>

## Limitations
- Low real-time accuracy
- Sensitive to lighting and background conditions
- Limited dataset and tuning

## Tech Stack
Python, OpenCV, Machine Learning, Computer Vision

## Requirements
- Python 3.x
- OpenCV
- TensorFlow / Keras
- NumPy
- Jupyter Notebook<br>
`pip install opencv-python numpy tensorflow`
