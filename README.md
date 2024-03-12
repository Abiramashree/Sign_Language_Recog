
# Sign Language Recognition
The goal is to create systems and software that can accurately and efficiently recognize the various hand gestures, facial expressions, and body movements and translate them into spoken or written language. 

Sign Language Recognition using Artificial Intelligence has been an area of interest for many years. Researchers have used several approaches and have achieved a lot of success in training different machine and deep learning models that can recognize signs corresponding to different words
This topic has several potential benefits, including making communication more accessible for deaf or hard-of-hearing individuals, allowing them to more easily interact with technology, and improving their ability to participate in various aspects of daily life.


## Features
- Uisng Mediapipe: which is an open-source framework from Google for building machine learning solutions. MediaPipe includes a hand tracking module that can detect and track the keypoints (or landmarks) of the human hand in real-time. These keypoints represent specific points on the hand, such as the tips of the fingers and the base of the palm, and they are used to infer the hand's pose and movements.
  <img width="732" alt="image" src="https://github.com/Abiramashree/Sign_Language_Recog/assets/100403590/9c262def-2f0d-4347-836c-2e090ff036c7">
- Collecting keypoints, instead of images for training a machine learning model can indeed reduce the amount of data needed and potentially increase accuracy, especially in scenarios where the keypoint representation captures essential information more efficiently than raw image data.


## Contents
- Training data(keypoint.csv)
- Label data(keypoint_classifier_label.csv)
- Training model(keypoint_classification.ipynb)
- Trained model(app.py)


## Results
I have trained the model for four signs: OK 👌🏻, All the Best 👍🏻, Peace ✌🏻, No 👆🏻(&Cross sign).
![image](https://github.com/Abiramashree/Sign_Language_Recog/assets/100403590/c46024dc-fa27-4cea-8658-cccea3a8de03)
