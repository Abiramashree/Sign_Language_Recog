# Sign Language Recognition
The goal is to create systems and software that can accurately and efficiently recognize the various hand gestures, facial expressions, and body movements and translate them into spoken or written language. 

Sign Language Recognition using Artificial Intelligence has been an area of interest for many years. Researchers have used several approaches and have achieved a lot of success in training different machine and deep learning models that can recognize signs corresponding to different words
This topic has several potential benefits, including making communication more accessible for deaf or hard-of-hearing individuals, allowing them to more easily interact with technology, and improving their ability to participate in various aspects of daily life.


## Features
- Uisng Mediapipe: which is an open-source framework from Google for building machine learning solutions. MediaPipe includes a hand tracking module that can detect and track the keypoints (or landmarks) of the human hand in real-time. These keypoints represent specific points on the hand, such as the tips of the fingers and the base of the palm, and they are used to infer the hand's pose and movements.
  
  <img width="425" alt="image" src="https://github.com/Abiramashree/Sign_Language_Recog/assets/100403590/9c262def-2f0d-4347-836c-2e090ff036c7">
- Collecting keypoints, instead of images for training a machine learning model can indeed reduce the amount of data needed and potentially increase accuracy, especially in scenarios where the keypoint representation captures essential information more efficiently than raw image data.


## Contents
- Training data(keypoint.csv)
- Label data(keypoint_classifier_label.csv)
- Training model(model.ipynb)
- Trained model(recog.py)


## Results
I have trained the model for four signs: OK 👌🏻, All the Best 👍🏻, Peace ✌🏻, No Waving👆🏻)(&Cross sign).

<img width="425" alt="image" src="https://github.com/Abiramashree/Sign_Language_Recog/assets/100403590/3cd8b3e8-9088-4d58-a708-cec22e0880c0">


## Usage
## Working
- Run app.py
- Make one of the signs 👍🏻 👌🏻 👍🏻 👆🏻
  
## To customise the model to recognise desired signs of yours 
- Remove all the contents in keypoint.csv and keypoint_classifier_label.csv
- Run app.py and press k to enter the mode to save key points (displayed as「MODE:Logging Key Point」
- Make the sign and press 0 for the first sign, 1 for second and so on (You can have upto 9 signs)
- Shift your hands and store as many signs you want (Have atleast 4 positions of the same sign for accurancy)
- You can see the keyposints beung added to the file keypoint.csv
- Run model.ipynb file to start the training the CNN model
- Run recog.py to open camera and see the gestures being deteted and classified

Reference:
Thanks to the open source repo https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe
