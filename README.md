# Blood Group Detection using Fingerprint

## 📌 Overview  
This project aims to detect a person's blood group using fingerprint analysis. By leveraging image processing techniques and a pre-trained machine learning model, we analyze the unique patterns in fingerprints to classify blood groups efficiently.

## 🚀 Features  
- Upload fingerprint images for blood group classification.  
- Image preprocessing using OpenCV and TensorFlow/Keras.  
- Pre-trained model for accurate predictions.  
- User-friendly web interface built with Flask.  

## 🛠️ Technologies Used  
- **Python**: Core programming language.  
- **Flask**: Web framework for building the application.  
- **TensorFlow/Keras**: For loading and using the pre-trained model.  
- **OpenCV**: For image preprocessing.  
- **NumPy**: For numerical computations.  

## 🔧 Installation  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/BrijeshRakhasiya/Blood-Group-Detection-using-Fingerprint.git
   cd Blood-Group-Detection-using-Fingerprint
   ```
2. **Install dependencies**:  
   ```bash
   pip install -r requirments.txt
   ```
3. **Run the application**:  
   ```bash
   python app.py
   ```
## 📂 Project Structure
Blood Group Detection using Fingerprint/
│
├── [app.py](http://_vscodecontentref_/1)                     # Main Flask application
├── model/
│   └── model.h5               # Pre-trained model
├── dataset_blood_group/       # Dataset of fingerprint images
│   ├── A+/                    # Example subdirectory for blood group A+
│   ├── B-/                    # Example subdirectory for blood group B-
│   └── ...                    # Other blood group subdirectories
├── templates/
│   └── index.html             # HTML template for the web interface
├── uploads/                   # Directory for uploaded files
├── requirements.txt           # Python dependencies
├── [README.md](http://_vscodecontentref_/2)                  # Project documentation
└── LICENSE                    # License file

## 📊 Dataset  
The dataset consists of fingerprint images categorized by blood groups. It is stored in the `dataset_blood_group/` directory, with subdirectories for each blood group (e.g., `A+`, `B-`, etc.).  

# 📌 How It Works
1. Users upload a fingerprint image through the web interface.
2. The image is preprocessed to match the model's input requirements.
3. The pre-trained model predicts the blood group based on the fingerprint patterns.
4. The result, including the predicted blood group and confidence score, is displayed to the user.

# 📌 Future Enhancements
1. Improve accuracy with advanced deep learning models.
2. Expand the dataset for better generalization.
3. Integrate a mobile application for easier access.


## 🤝 Contributing  
- Contributions are welcome! Feel free to fork, raise issues, or submit pull requests.  
- Fork the repository.  
- Create a new branch for your feature/bugfix.  
- Commit your changes.  
- Submit a pull request.  

## 📜 License  
- This project is licensed under the MIT License. See the LICENSE file for details.  

## 🙏 Acknowledgments  
- Thanks to OpenCV and TensorFlow for providing the tools needed for this project.  
- Special thanks to the contributors of the dataset used in this project.  

## 📧 Contact  
- For any questions or feedback, feel free to reach out:  

Email: brijeshrakhasiya.aiml@gmail.com  

GitHub: BrijeshRakhasiya


