# darknetMUEAVI

repo cloned from:
https://github.com/AlexeyAB/darknet

# darknet usage

export LD_LIBRARY_PATH=/usr/local/cuda-9.2/lib64:$LD_LIBRARY_PATH

export PATH=/usr/local/cuda-9.2/bin:$PATH

yolov3.cfg (236 MB COCO Yolo v3) - requires 4 GB GPU-RAM: https://pjreddie.com/media/files/yolov3.weights

# basic example

./darknet detector test cfg/coco.data cfg/yolov3.cfg cfg/yolov3.weights -ext_output data/dog.jpg
