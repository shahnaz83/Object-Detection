### Object Detection with YOLOv3-tiny and   OpenCV

#### In Object detection you want to predict the location of an object in an image by placing a bounding box around it.

In this notebook, we will setup object detection with Yolov3-tiny and OpenCV on images and a video(A video from the streets of Tehran).
I downloaded the config, weights from https://pjreddie.com/darknet/yolo/. We also can setup YOLO with darknet and run it as a bellow:


```python
# clone darknet repo
#!git clone https://github.com/AlexeyAB/darknet
```


```python
# change makefile to have GPU and OPENCV enabled
#%cd darknet
```


```python
# make darknet (builds darknet so that you can then use the darknet executable file to run or train object detectors)
#!make
```


```python
#!wget https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov4.weights
```


```python
#!./darknet detector test <path to .data file> <path to config> <path to weights> <path to image>
```
