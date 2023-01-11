# ASL-Translator-Flask-Web-App
Flask Web app for previous work done to translate American Sign Language through webcam feed. 

## Intro:
Deafness and sign language are the largest and hardest to overcome language barriers in the modern world. In this case it isn't feasible to "learn" or even attempt to 
bridge this gap through self-study. Here we aim to aid in crossing this gap through the creation of a lightweight and truely robust ASL(American Sign-Language) 
detection model that could take a live feed from a user's camera and translate word and alphabet level sign in real-time to english. The realisation of such a project 
would surely aid in day to day life in order to connect more people together through seemless conversation.

The repository itself contains 3 Files:

#### asl-model_GC.pth
- This file has all the pretrained weights to translate ASL sign images.

#### App.py
- This launches the web app on a local server using flask to 127.0.0.1:5000 where you can see in real time what signs you're making by doing inference with CPU.

#### Index.html 
- Very basic HTML page to display video and predictions in real time.

## Modeling Project Overview

### Realtime example:

![alt text](https://github.com/MarkoLewis-Projects/Sign_language_detection/blob/main/hand_detection_clipped.gif "Resnet34 detection")

### Future Work (Word Level):

As mentioned previously the computational intensity of high-accuracy video recognition is a large factor in making full sign recognition difficulty.
Because of this Inference would also be computationally demanding requiring long times making it impractical in the real world.

### Past Project:

- https://github.com/MarkoLewis-Projects/Sign_language_detection
