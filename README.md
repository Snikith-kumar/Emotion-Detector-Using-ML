# Emotion-Detector-Using-ML
Real-time facial emotion recognition using OpenCV and Mini-XCEPTION
Table of Content :

1.Description
2.Installations
3.Usage
4.Dataset


![Screenshot 2025-07-07 215751](https://github.com/user-attachments/assets/6d2446a0-8d59-4d0c-b7b1-224c17c1cad5)

Description:
Our Human face is having a mixed emotions so we are to demonstrate the probabilities of these emotions that we have.

What does Emotion Recognition mean?
Emotion recognition is a technique used in software that allows a program to "read" the emotions on a human face using advanced image processing. Companies have been experimenting with combining sophisticated algorithms with image processing techniques that have emerged in the past ten years to understand more about what an image or a video of a person's face tells us about how he/she is feeling and not just that but also showing the probabilities of mixed emotions a face could has.

Installations:
Install dependencies using requirements.txt

pip install -r requirements.txt

Usage:
The program will creat a window to display the scene capture by webcamera and a window representing the probabilities of detected emotions.

Demo

python real_time_video.py

You can just use this with the provided pretrained model i have included in the path written in the code file, i have choosen this specificaly since it scores the best accuracy, feel free to choose any but in this case you have to run the later file train_emotion_classifier

If you just want to run this demo, the following content can be skipped

Train

python train_emotion_classifier.py


Dataset:

The model is trained on the FER-2013 dataset.

Ongoing
Draw emotions faces next to the detected face.




