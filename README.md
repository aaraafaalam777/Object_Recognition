🎯 Real-Time Object Recognition using CNN & OpenCV

A computer vision project that performs real-time object recognition using a custom Convolutional Neural Network (CNN) trained on webcam-captured images.
The system supports live data collection, training, and prediction using OpenCV and TensorFlow/Keras.

🚀 Features
📸 Real-time image collection using webcam
🗂️ Automatic dataset organization by class
🔄 Data augmentation for better generalization
🧠 Custom CNN model built from scratch
🎥 Live object recognition using webcam feed
💾 Model saving & loading
🧪 Train/Validation split with performance tracking

🛠️ Tech Stack
Python
OpenCV
TensorFlow / Keras
NumPy
OS module

📦 Supported Object Classes
mobile
bottle
book
headphone
mouse


You can easily add more classes by updating the class list and retraining.

📁 Project Structure
object-recognition/
│
├── dataset/
│   ├── mobile/
│   ├── bottle/
│   ├── book/
│   ├── headphone/
│   └── mouse/
│
├── data_collection.py
├── train_model.py
├── real_time_prediction.py
├── object_model.h5
├── requirements.txt
└── README.md

Output
Images are:
Cropped using ROI
Resized to 128×128
Stored in dataset/class_name/

🧠 Step 2: Model Training
Data Preprocessing
Image normalization

Data augmentation:
Rotation
Zoom
Horizontal flip
Train/Validation split: 80% / 20%

Future Enhancements
📊 Confidence score display
🧠 Transfer learning (MobileNet / ResNet)
🏷️ Dynamic class addition
📹 Video file recognition
📱 Mobile / Edge deployment
🧪 Model accuracy visualization
