Car License Plate Detector
Overview

This project aims to detect the license plates of cars using YOLOv7 object detection. We collected a dataset of images of cars and their annotations from Kaggle, which we then converted to YOLOv7 format. We used YOLOv7 to train a model and implemented gradient accumulation to improve the accuracy of the model. The resulting weights file is saved here as yolov7.pt.
Usage

To detect license plates in your own images, use the extraction.ipynb file. This file uses YOLOv7's built-in detect.py script to detect license plates in the images. The detected license plates are then saved in a separate folder and displayed in the notebook.

To use the extraction.ipynb file, make sure you have the following files in the same directory:

    extraction.ipynb
    yolov7.pt
    A folder containing the images you want to detect license plates in

Open the extraction.ipynb file and run the cells. The detected license plates will be saved in a folder called detections and displayed in the notebook.
Credits

This project was made possible by the following resources:

    YOLOv7: https://github.com/WongKinYiu/yolov7
    Dataset of car images and annotations: Kaggle
