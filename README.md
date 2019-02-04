# darknetMUEAVI

# darknet usage

export LD_LIBRARY_PATH=/usr/local/cuda-9.2/lib64:$LD_LIBRARY_PATH

export PATH=/usr/local/cuda-9.2/bin:$PATH

# basic example

./darknet detector test cfg/coco.data cfg/yolov3.cfg cfg/yolov3.weights -ext_output data/dog.jpg
