
✋ **Hand Sign Detection using Deep Learning**

Welcome to HandSignDetection, a deep-learning based project designed to recognize hand gestures from live camera feed.
This system can be used for sign language recognition, gesture-based interaction, and accessibility tools.

🚀 Features

✅ Real-time hand sign detection

✅ Trained CNN model for gesture classification

✅ Dataset folders for custom training

✅ Modular Jupyter Notebooks:

trainer.ipynb → Train the model

main.ipynb → Run prediction using webcam

✅ .h5 trained model + .npy labels included

🧠 **Model Overview**
Component	Description
Model Type	Convolutional Neural Network (CNN)
Framework	TensorFlow / Keras
Input	Hand gesture images
Output	Predicted sign label
Training	Limited dataset for prototype stage

The project currently supports limited signs due to early development.
You can expand the dataset to cover full A-Z & functional signs (space, delete, etc.)

📦 <br>**Installation**</br>
1️⃣ Clone the repo
git clone https://github.com/TheShr/HandSignDetection.git
cd HandSignDetection

2️⃣ Install dependencies
pip install tensorflow opencv-python numpy matplotlib


✨ **Future Improvements**

Expand dataset to full sign language set

Use MediaPipe for better hand landmark extraction

Build Flask backend & web UI

Convert model into TensorFlow Lite for mobile apps

Add speech output for detected signs

🎯 Goal

This is a foundational sign language recognition model intended for:

Learning deep learning & image classification

Accessibility applications

Gesture-based UI systems

Future AI-driven assistive tech

📚 Credits

This project was developed to explore Computer Vision + Deep Learning applications in sign language understanding.

🛠️ Author

Anuj Sharma
B.Tech CSE, Bennett University

⭐ Support


