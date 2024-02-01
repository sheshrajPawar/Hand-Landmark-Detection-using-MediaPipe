# Hand-Landmark-Detection-using-MediaPipe
This repository contains a Python script for hand landmark detection using the MediaPipe library. The script can process static images or perform real-time hand landmark detection using a webcam.

# 1. Introduction:
The repository provides a Python script for hand landmark detection using the MediaPipe library. This technology allows the identification and tracking of key points on the human hand.

# 2. Dependencies:
The code relies on two main libraries: OpenCV (cv2) and MediaPipe (mediapipe).
These libraries facilitate image processing, camera input, and hand landmark detection.

# 3. Static Image Processing:
a. Image Loading:
The script starts by loading a set of static images specified in the IMAGE_FILES list.
b. Hand Landmark Detection:
Utilizing the mp_hands.Hands class in static image mode, the code processes each image to detect hand landmarks.
It prints information about handedness and identifies hand landmarks in the images.
c. Annotation and Saving:
The detected landmarks are annotated on the images, including information about the index finger tip coordinates.
Annotated images are saved in the /tmp/ directory.

# 4. Webcam Input:
a. Webcam Initialization:
The code sets up the default camera using OpenCV's cv2.VideoCapture.
b. Real-time Hand Landmark Detection:
The mp_hands.Hands class is again employed, this time in real-time mode, to continuously process video frames from the webcam.
Detected hand landmarks are drawn on the frames.
c. Display and Exit:
Annotated frames are displayed in a window named "MediaPipe Hands," allowing real-time observation.
The application runs until the 'Esc' key is pressed, providing a smooth exit from the webcam mode.

# 5. Dependencies and License:
A brief section mentions the required dependencies (cv2 and mediapipe) and the open-source nature of the project under the MIT License.

# 6. Conclusion:
The repository offers a comprehensive solution for hand landmark detection, whether through static images or real-time webcam input. Users can easily integrate this code into their projects and explore the fascinating field of computer vision and hand gesture analysis.



