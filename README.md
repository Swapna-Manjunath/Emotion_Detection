# Recognition of Face Emotion in Real-Time using OpenCV 
<br>
<b>Overview:</b> <br>
This project implements a real-time facial emotion recognition system using OpenCV for face detection and the DeepFace library for emotion analysis. The application captures live video from a webcam, detects faces, and classifies their emotions.
<br><br>
<b>Features:</b><br>
Real-time face detection using Haar cascades.<br>
Emotion analysis using the DeepFace library with pre-trained models.<br>
Annotates detected faces with their dominant emotion in the video feed.<br>
Simple and intuitive implementation with minimal dependencies.<br> <br>
<b>Technologies Used:</b> <br>
Python: Core programming language. <br>
OpenCV: For video capture, face detection, and frame manipulation. <br>
DeepFace: For deep learning-based emotion recognition. <br>
Haar Cascades: For real-time face detection. <br><br>
<b>Project Workflow:</b><br>
Face Detection:
Uses OpenCV’s Haar cascades to detect faces in real-time.<br>
Emotion Analysis:
The DeepFace library analyzes each detected face and predicts the dominant emotion.<br>
Display Results:
The detected emotion is displayed alongside a bounding box around the face.<br><br>
<b>Output Example Emotions are:</b><br>
Happy,
 Sad,
 Angry,
 Neutral,
 Fearful,
 Surprised.
