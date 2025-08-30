Hand Gesture Recognition using CNN (LeapGestRecog Dataset)
This project implements a hand gesture recognition system using deep learning (CNN with transfer learning).
It uses the LeapGestRecog dataset consisting of 200,000 images across 10 different gesture classes, collected using a Leap Motion Controller.

📂 Dataset
Dataset Name: LeapGestRecog
Classes (10 Gestures):
Palm
L
Fist
Fist Moved
Thumb
Index
OK
Palm Moved
C
Down
👉 Download here: LeapGestRecog Dataset on Kaggle

🚀 Features
Preprocessing pipeline with TensorFlow & Keras
CNN-based model with transfer learning (e.g., MobileNetV2 / EfficientNet)
Fine-tuning last layers for improved accuracy
Training, validation, and prediction support
Achieved ~35%+ accuracy after fine-tuning (can be improved with more epochs & augmentation)
📦 Requirements
Install dependencies:

pip install tensorflow keras opencv-python matplotlib numpy
