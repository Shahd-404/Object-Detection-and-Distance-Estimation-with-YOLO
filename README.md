# Object Detection and Distance Estimation with YOLO

![Screenshot](Screenshot%202024-11-28%20230030.png)

## 1. Setup the Environment
### Install required libraries and dependencies.
### Load the YOLO pre-trained weights and configuration files.
## 2. Import Libraries
### Import necessary libraries such as cv2, numpy, matplotlib, gTTS, etc.
## 3. Load YOLO Model
### Load the YOLO configuration file (yolov3.cfg) and the pre-trained weights (yolov3.weights).
### Load the class names (coco.names).
## 4. Preprocess Input Data
### Load the image or video frame.
### Resize and normalize the input data for YOLO model compatibility.
## 5. Perform Object Detection
### Pass the image or video frame through the YOLO network.
### Detect the bounding boxes, class IDs, and confidence scores for each object.
## 6. Filter Object Detections
### Apply Non-Maximum Suppression (NMS) to filter out redundant detections.
### Display the bounding boxes and class labels for detected objects.
## 7. Distance Estimation
### Calculate the estimated distance for each object detected, based on object size and camera parameters.
### Use the known dimensions of objects to estimate distances (e.g., person, car).
## 8. Text-to-Speech Feedback
### Use the gTTS library to convert the object and distance information into speech.
### Output the speech to inform the user of the detected objects and their estimated distances.
## 9. User Interaction
### Prompt the user to input the object to detect (e.g., "person", "car").
### Suggest possible matches if the user’s input is incorrect.
## 12. Display Results
### Display the detected objects with bounding boxes on the image or video stream.
### Show the estimated distances of the detected objects.

