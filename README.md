# AI-Lab
Computer Identification Using Deep Learning and OpenCV

This repository contains a deep learning-based computer vision model developed to identify the type of computer—Mac or Windows—using a live camera feed. The model is trained on thousands of images of Mac, Windows, and other laptops. It uses OpenCV to capture the camera feed and determine the type of computer in real-time.

Project Overview

The deep learning model was trained using a large dataset containing images of various types of computers, specifically focusing on Mac and Windows laptops. The trained model is integrated with OpenCV, which allows real-time identification through the camera feed. The program classifies the computer based on visual features captured by the camera.

Key Features

Real-Time Computer Identification: Uses a webcam or connected camera to detect whether the computer is a Mac or Windows machine.
Deep Learning Model: The model is based on a deep learning architecture trained on thousands of images of Mac and Windows computers.
OpenCV Integration: OpenCV is used for video capture and image processing.

Requirements

Python 3.x
OpenCV
TensorFlow or Keras (depending on your model)
NumPy

You can install the required dependencies using pip:

pip install -r requirements.txt

Usage

To run the computer identification model, execute the following command:

python computer_identification.py
The program will open the camera feed, analyze the frames in real-time, and display the type of computer detected on the screen. The prediction will be shown as "Mac" or "Windows" in a text box overlaid on the camera feed.

Model Training

The deep learning model was trained on a dataset consisting of images from both Mac and Windows laptops. The training process involved the following steps:

Data Collection: Thousands of images of different laptops were collected.
Preprocessing: The images were resized and normalized before being fed into the model.
Model Architecture: (Describe the architecture of the model used, such as CNN, ResNet, etc.)
Training: The model was trained for several epochs until it reached an acceptable accuracy.
Model Evaluation

Once trained, the model was evaluated on a separate validation set to ensure its generalization ability. The accuracy, precision, recall, and F1 score were used as the primary evaluation metrics.

How It Works

Camera Feed Capture: OpenCV is used to capture frames from the webcam.
Image Preprocessing: Each frame is preprocessed before being passed to the trained model.
Prediction: The model predicts whether the computer in the frame is a Mac or Windows machine.

Output: The prediction is displayed on the screen in real-time.

Contributing

Feel free to fork this repository and submit issues or pull requests. Contributions to improve the model or add new features are welcome!

License

This project is licensed under the MIT License - see the LICENSE file for details.
