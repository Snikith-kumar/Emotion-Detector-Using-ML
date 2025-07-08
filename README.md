# Emotion-Detector-Using-ML
Real-time facial emotion recognition using OpenCV and Mini-XCEPTION
# Emotion Detector Using ML 🎭  
Real-time facial emotion recognition using OpenCV and Mini-XCEPTION.

---

## 📑 Table of Contents
1. [Description](#description)  
2. [Installations](#installations)  
3. [Usage](#usage)  
4. [Dataset](#dataset)  
5. [Demo Screenshot](#demo-screenshot)  



---

## 🧠 Description

Emotion recognition is a computer vision technique used to "read" human emotions from facial expressions using deep learning and image processing. This project demonstrates how human faces often show mixed emotions, and visualizes the probability distribution across seven basic emotions.

Using a pre-trained Mini-XCEPTION model trained on the FER-2013 dataset, the system detects faces and classifies emotions in real time, displaying both the predicted emotion and a probability bar chart.

---

## ⚙️ Installations

Install all required dependencies with:

```bash
pip install -r requirements.txt


▶️ Usage
To run the real-time emotion detection demo:

python real_time_video.py

A webcam window will display detected faces with predicted emotion labels.
A second window shows a bar chart of emotion probabilities.
If you want to train your own model, use:

python train_emotion_classifier.py

## 📸 Demo Screenshot

[<img src="https://github.com/user-attachments/assets/b32d22ac-77c0-4749-95d5-8c4daf380959" width="500"/>](https://github.com/user-attachments/assets/b32d22ac-77c0-4749-95d5-8c4daf380959)




