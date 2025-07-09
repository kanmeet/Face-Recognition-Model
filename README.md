
# 👁️ Face Recognition System using OpenCV

A Computer Vision project to recognize human faces using OpenCV in real-time. The system supports image collection, model training using the LBPH algorithm, and live face recognition via webcam.

---

## 📁 Project Structure

```
face-recognition-model/
├── data/                         # Collected face images per person
│   └── Person_Name/              
├── models/                       # Trained model and label encodings
│   ├── lbph_model.xml
│   └── label_encoder.pkl
├── Computer_vision_part1.ipynb   # Notebook for image collection
├── Face_recognition Part2.ipynb  # Notebook for training and recognition
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 🚀 Features

- 🧠 Face detection using Haar Cascades  
- 🔍 Face recognition using LBPH (Local Binary Patterns Histograms)  
- 📷 Real-time webcam-based recognition  
- 📁 Save and reload trained models  

---

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/face-recognition-model.git
cd face-recognition-model
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Collect Face Images

Run the notebook:

```bash
Computer_vision_part1.ipynb
```

- Enter the name of the person
- Collect ~50 images using webcam

### 4. Train the Model

Run the notebook:

```bash
Face_recognition Part2.ipynb
```

- This will train the LBPH model
- Saves the model and label encoder

### 5. Run Real-Time Recognition

Continue in the same notebook to launch webcam recognition.  
It will detect and label known faces live.

---

## 🧰 Tech Stack

- Python 3.x  
- OpenCV (opencv-contrib-python)  
- NumPy  
- Pickle (for label encoding)

---

## 📄 requirements.txt

```
opencv-contrib-python
numpy
```

---

## 📌 Future Improvements

- Replace LBPH with FaceNet or Dlib embeddings  
- Add GUI using Streamlit or Flask  
- Store training data in cloud or database  

---

---

## 📜 License

This project is licensed under the MIT License.
