# Car-Detection-using-YOLO
Convolutional implementation of object detection on a car dataset using YOLO model, further modified using a U-net architecture.

YOLO ("you only look once") is a popular algoritm because it achieves high accuracy while also being able to run in real-time, almost clocking 45 frames per second. A smaller version of the network, Fast YOLO, processes an astounding 155 frames per second while still achieving double the mAP of other real-time detectors. This algorithm "only looks once" at the image in the sense that it requires only one forward propagation pass through the network to make predictions. After non-max suppression, it then outputs recognized objects together with the bounding boxes.
