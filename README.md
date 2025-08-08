YOLOv11 Object Detection
This project uses the Ultralytics YOLO framework to train and run object detection on custom data.

Features
Model: YOLO11s (COCO-pretrained, small model)

Training: Custom dataset (data.yaml) with 640×640 images

Prediction: Runs inference on videos with adjustable confidence threshold

Output: Saves annotated results automatically

Note:
The model is trained on a small YOLO11s architecture for only 2 epochs because I don’t have a high-end PC.
As a result, the accuracy is limited. This can be improved by:

Increasing the number of epochs

Using a larger dataset

Training on a more powerful model