# fruit-classification
This simple project aims to develop models to sort apples, bananas and pears correctly

fruit-classification/
├── dataset/      # Fruit360 dataset
│   ├── apple/
│   ├── banana/
│   └── pear/
├── notebooks/
    ├── Fruit_classification_SVM.ipynb
│   └── Fruit_classification_CNN.ipynb
└── README.md

## 🔍 Objective
To develop an image classification models that accurately identifies fruit type from images using deep learning, specifically Convolutional Neural Networks and Support Vector Machines (evaluating the importance of certain features for the SVM).

## 🧠 Methodology
- Data preprocessing: resizing, normalization, and data augmentation.
- Model architecture: a simple CNN with Conv2D, MaxPooling, and Dense layers.
- Training using cross-entropy loss and Adam optimizer.
- Evaluation on test set using accuracy, confusion matrix, and classification report.

## 🛠️ Tools & Libraries
- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- scikit-learn
- Matplotlib

📈 Results
- The models achieved: 99% accuracy with the SVM achieiving varying accuracy depending on the altered features
- Fast and reliable inference on test images

Link to dataset: https://drive.google.com/drive/folders/1w09Iv5z9s1yW_J_vJBwD4lVcRMwai9ql?usp=sharing
