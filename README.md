# Blood Group Detection using Fingerprint


This project aims to detect an individual's blood group using their fingerprint. It leverages image processing and machine learning techniques to analyze fingerprint patterns and predict the blood group.

---

## Features
- **Fingerprint Analysis**: Extracts unique features from fingerprint images.
- **Blood Group Prediction**: Predicts blood group (A, B, AB, O) based on fingerprint data.
- **User-Friendly Interface**: Simple and intuitive interface for easy interaction.
- **Dataset Integration**: Works with a pre-processed dataset of fingerprints and corresponding blood groups.

---

## Technologies Used
- **Python**: Primary programming language.
- **OpenCV**: For image processing and fingerprint analysis.
- **Scikit-learn**: For machine learning model training and evaluation.
- **TensorFlow/Keras**: For deep learning-based feature extraction (if applicable).
- **Flask/Django**: For creating a web-based interface (optional).

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/BrijeshRakhasiya/Blood-Group-Detection-using-Fingerprint.git
   cd Blood-Group-Detection-using-Fingerprint


  Project Structure
Blood-Group-Detection-using-Fingerprint/
├── dataset/               # Contains fingerprint images and labels
├── models/                # Trained machine learning models
├── src/                   # Source code for the project
│   ├── preprocessing.py   # Image preprocessing scripts
│   ├── feature_extraction.py  # Feature extraction scripts
│   ├── train_model.py     # Model training scripts
│   ├── predict.py         # Prediction script
│   └── app.py             # Main application script (if applicable)
├── requirements.txt       # List of dependencies
└── README.md              # Project documentation
