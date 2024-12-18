# Recognition of Face Emotion in Real-Time using OpenCV 
<br>
<b><u>Overview:</u></b> <br>
This project implements a real-time facial emotion recognition system using OpenCV for face detection and the DeepFace library for emotion analysis. The application captures live video from a webcam, detects faces, and classifies their emotions.
<br><br>
<b><u>Features:</u></b><br>
Real-time face detection using Haar cascades.<br>
Emotion analysis using the DeepFace library with pre-trained models.<br>
Annotates detected faces with their dominant emotion in the video feed.<br>
Simple and intuitive implementation with minimal dependencies.<br> <br>
<b><u>Technologies Used:</u></b> <br>
<b>Python:</b> Core programming language. <br>
<b>OpenCV:</b> For video capture, face detection, and frame manipulation. <br>
<b>DeepFace:</b> For deep learning-based emotion recognition. <br>
<b>Haar Cascades:</b> For real-time face detection. <br><br>
<b><u>Project Workflow:</u></b><br>
<b>Face Detection:</b>
Uses OpenCV’s Haar cascades to detect faces in real-time.<br>
<b>Emotion Analysis:</b>
The DeepFace library analyzes each detected face and predicts the dominant emotion.<br>
<b>Display Results:</b>
The detected emotion is displayed alongside a bounding box around the face.<br><br>
<b><u>Output Example Emotions are:</u></b><br>
Happy,
 Sad,
 Angry,
 Neutral,
 Fearful,
 Surprised.
