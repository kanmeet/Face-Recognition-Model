👁️‍🗨️ Face Recognition System using OpenCV
A complete Computer Vision pipeline for real-time face recognition using OpenCV and Python. This project includes image dataset collection, model training using LBPH algorithm, and real-time face recognition from webcam feed.

🧠 Overview
This repository demonstrates a step-by-step approach to building a face recognition system using:

OpenCV for image handling and webcam capture

Haar Cascade for face detection

LBPH (Local Binary Patterns Histogram) for face recognition

🗂️ Project Structure
'''
face-recognition-model/
├── data/                         # Collected face images per person
│   └── Person_Name/              # Example: data/Kartik/
├── models/                       # Trained model and label encodings
│   ├── lbph_model.xml
│   └── label_encoder.pkl
├── Computer_vision_part1.ipynb   # Notebook for image collection
├── Face_recognition Part2.ipynb  # Notebook for training and recognition
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation 
'''


🔧 Features
📷 Capture face images for training via webcam

👨‍🏫 Train a face recognizer using LBPH algorithm

🎯 Real-time face detection and recognition

🧱 Modular design with clean code separation

🚀 Getting Started
1. Clone the repository
git clone https://github.com/<your-username>/face-recognition-model.git
cd face-recognition-model

3. Install dependencies
pip install -r requirements.txt

4. Collect training images
Open the notebook:
Computer_vision_part1.ipynb

Capture multiple images (suggested: 50–100 per person)

4. Train the model
Face_recognition Part2.ipynb

Trains the LBPH face recognizer

Saves model file (e.g., lbph_model.xml) and label encoding

🧰 Tech Stack
Python 3.x

OpenCV (opencv-contrib-python)

NumPy

Pickle (for label encoding)

📁 Requirements
opencv-contrib-python
numpy
✅ Future Enhancements
Add deep face embeddings (FaceNet, Dlib, ArcFace)

Replace notebook interface with Streamlit or Flask app

Improve accuracy with image preprocessing
