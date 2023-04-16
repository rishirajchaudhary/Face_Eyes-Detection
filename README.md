# Face-Eyes-Detection
This project aims to build a real-time face and eyes detection system using OpenCV. The Haar Cascade classifier is used to detect faces and eyes, and the system can be used to process a live video stream or a recorded video file. The detected faces and eyes are highlighted using rectangles. 

# Getting Started
Clone this repository to your local machine.
Install OpenCV and numpy using pip install opencv-python numpy.
Prepare a video file or live video stream to test the system.

# Face and Eyes Detection
The face detection is done using the Haar Cascade classifier, which is a machine learning-based approach.
The eyes detection is done using the Haar Cascade classifier trained specifically for eyes detection.
The classifiers are loaded into the system using the cv2.CascadeClassifier function.
The detection is performed on each frame of the video stream or recorded video file using the detectMultiScale function, which returns the coordinates of the detected faces and eyes.
The coordinates are used to draw a rectangle around the detected faces and eyes using the cv2.rectangle function.

# Real-Time Detection
To perform real-time detection, we capture the frames from the webcam or video file using the cv2.VideoCapture function.
We continuously process each frame and display the output using the cv2.imshow function.
The program exits when the user presses the 'q' key.

# Results
The face and eyes detection system successfully detects and highlights human faces and eyes in real-time from a live video stream or recorded video file.

# Conclusion
In this project, we successfully built a real-time face and eyes detection system using OpenCV. The system can detect and highlight human faces and eyes from a live video stream or recorded video file. The project demonstrates the effectiveness of the Haarcascade classifier for face and eyes detection and the versatility of OpenCV in computer vision applications.

# Real-time detection example
<img width="253" alt="face_detect" src="https://user-images.githubusercontent.com/84733746/232330102-699e6472-1b5e-424c-977a-5df580ee02e2.png">
