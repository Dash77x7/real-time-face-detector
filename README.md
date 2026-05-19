Real-Time Face Detector using OpenCV
About
This project captures live webcam video and detects faces in real time using OpenCV's Haar Cascade Classifier in Python.
Technologies Used

Python 3.x
OpenCV (cv2)
Haar Cascade Classifier

How to Run
Step 1 - Install dependencies
pip install opencv-python
Step 2 - Run the script
python face_detector.py
Step 3 - Quit
Press 'q' on your keyboard to quit the webcam window.
How it Works

Captures each frame from the webcam
Converts each frame to grayscale for faster processing
Runs Haar Cascade face detection on each frame
Draws green rectangles around all detected faces
Shows the count of faces detected in real time

Technologies and Concepts Learned

OpenCV VideoCapture for webcam access
Haar Cascade Classifier for face detection
Image processing with grayscale conversion
Real-time video frame processing

Assignment
This project was built as part of Assignment M4 of my AI/ML course.
