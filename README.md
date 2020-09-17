
# Car_Dectection_YOLO
Detecting the car and other objects using YOLO algoritham

Object detection is one of the classical problems in computer vision where you work to recognize what and where — specifically what objects are inside a given image and also where they are in the image. 
The problem of object detection is more complex than classification, which also can recognize objects but doesn’t indicate where the object is located in the image. In addition, classification doesn’t work on images containing more than one object.
YOLO is popular because it achieves high accuracy while also being able to run in real-time. 
The algorithm “only looks once” at the image in the sense that it requires only one forward propagation pass through the neural network to make predictions. 
After non-max suppression (which makes sure the object detection algorithm only detects each object once), it then outputs recognized objects together with the bounding boxes.
# Key Important points for YOLO algoritham.
With YOLO, a single CNN simultaneously predicts multiple bounding boxes and class probabilities for those boxes. 
YOLO trains on full images and directly optimizes detection performance. This model has a number of benefits over other object detection methods:
YOLO is extremely fast and sees the entire image during training and test time so it implicitly encodes contextual information about classes as well as their appearance.
YOLO learns generalizable representations of objects so that when trained on natural images and tested on artwork, the algorithm outperforms other top detection methods.
# About the project
-The project is implemented as a project to detect the car and other object using yolo algoritham using one forward prpogation.
## Sources
-Wikipedia (https://en.wikipedia.org/wiki/Object_detection)
-Medium (https://medium.com/@ODSC/overview-of-the-yolo-object-detection-algorithm-7b52a745d3e0)
