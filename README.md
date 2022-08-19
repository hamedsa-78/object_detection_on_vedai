This repository is designed to be used with keras-retinanet - Fizyr's popular Keras implementation of the RetinaNet object detection and YOLOv5 🚀 in PyTorch > ONNX > CoreML > TFLite  for object detection task on Vehicle Detection in Aerial Imagery (VEDAI) dataset.

here there are some useful scripts fro preprocessing datas on dataset and some other useful functions that can be used in any project of object detection on Retina-Net and Yolov:
* Prepare your dataset (both training and test sets) in the CSV format required for training and evaluation with keras-retinanet (build_dataset.py)
* Generate predictions (get all predicted boxes of retina net that are candidate for matching real boxes (predit_boxes.py)
* convert train.csv and test.csv files to data format that yolov5 expecting  (build_yolov5_dataset.py)

the Jupyter Notebooks of this task on retina net and Yolov5 are also there.

