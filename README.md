# Object-detection-using-web-camera
# DEVELOPED BY:Kannan N
# REGISTER NUMBER: 212223230097
# AIM:
To detect and identify real-time objects from a live webcam feed using the YOLOv4 (You Only Look Once) deep learning model.

## PROCEDURE:
STEP1:
Import required libraries (cv2, numpy).

STEP2:
Load YOLOv4 model (.weights and .cfg) and COCO class labels.

STEP3:
Initialize webcam video capture.

STEP4:
For each frame: 1.Convert the frame to a blob and pass it through YOLO. 2.Detect objects, filter by confidence, and apply Non-Max Suppression. 3.Draw bounding boxes and labels on detected objects.

STEP5:
Display the frames in real-time.

STEP6:
Exit on pressing ‘q’ and release resources.

STEP7:
Display the saved image of object detection results using an image viewer or plotting library.
