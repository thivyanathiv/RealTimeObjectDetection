**Project Description**
This project implements a real-time object detection system using the YOLOv3 (You Only Look Once) algorithm. 
The application captures video from a webcam, processes it through a pre-trained YOLO model, and identifies objects in the video feed with bounding boxes and labels. 
The project demonstrates the effectiveness of YOLO for real-time object detection and classification.

**Features**
Real-time object detection and classification.
High accuracy and speed using the YOLOv3 deep learning model.
Detection of multiple object classes defined in the COCO dataset.
Visual display of bounding boxes and labels with confidence scores.

**Technologies Used**
Programming Language: Python
Libraries: OpenCV, NumPy

**Model Files**
yolov3.weights - Pre-trained weights for the YOLOv3 model.
yolov3.cfg - Configuration file for the YOLOv3 architecture.
coco.names - List of class labels trained on the COCO dataset.

Install Dependencies
Make sure Python is installed. Then install the required libraries
**pip install opencv-python numpy**

Download YOLO Model Files
Download the YOLOv3 model files
yolov3.weights
yolov3.cfg
coco.names
Place these files in the project directory.

Run the script
**python object_detection.py**

The application will open a window with real-time object detection from your webcam.
Press **q** to exit the application.



