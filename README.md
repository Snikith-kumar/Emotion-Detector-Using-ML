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


![Screenshot 2025-07-07 215751](https://github.com/user-attachments/assets/6d2446a0-8d59-4d0c-b7b1-224c17c1cad5)



##Demo

python real_time_video.py

You can just use this with the provided pretrained model i have included in the path written in the code file, i have choosen this specificaly since it scores the best accuracy, feel free to choose any but in this case you have to run the later file train_emotion_classifier

If you just want to run this demo, the following content can be skipped

Train

python train_emotion_classifier.py


##Dataset:

The model is trained on the FER-2013 dataset.

Ongoing
Draw emotions faces next to the detected face.

--
![Screenshot 2025-07-07 215751](https://github.com/user-attachments/assets/6d2446a0-8d59-4d0c-b7b1-224c17c1cad5)


