# Hand Signal Detection using OpenCV

This project is a Python script that uses OpenCV to detect and track hand signals in real-time video streams from a webcam.

Getting Started
To run this script, you will need to install the OpenCV library for Python. You can do this using pip by running the following command:

pip install opencv-python
You will also need to download the haarcascade_frontalface_default.xml file, which is used for face detection. You can download it from the OpenCV GitHub repository at the following URL: https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml

Save this file to the same directory as the script.

Usage
To use this script, simply run it in a Python environment, such as IDLE or Jupyter Notebook. The script will open your default webcam and display the video stream in a new window titled "Hand Signals".

The script detects faces and hands in the video stream using two different methods:

Face detection: using the Haar Cascade classifier haarcascade_frontalface_default.xml.
Hand detection: by applying color-based segmentation using HSV color space, then applying erosion and dilation to remove noise and isolate the hand contours.
Detected faces and hands are highlighted with a rectangle and labeled with the words "Face" and "Hand", respectively.

Press the "q" key to quit the script and close the video stream window.

Contributing
Contributions are welcome! If you find any bugs or have any suggestions for improvements, please feel free to create an issue or pull request on the GitHub repository at https://github.com/AashishH15/Hand-Face-Detection.
