
# Helmet Tracking

It is a simple Object detection model that tracks and counts people wearing helmet from a Traffic video


## Requirements
installing the below packages is the primary Requirements


    pip install tensorflow

    pip install opencv-python










## About Data

The data for this project has been collected from kaggle .

This dataset contains 764 images of 2 distinct classes for the objective of helmet detection.
Bounding box annotations are provided in the PASCAL VOC format
The classes are:

•With helmet

•Without helmet

link: https://www.kaggle.com/datasets/andrewmvd/helmet-detection

## Object Detection

For this project I have used the Tensorflow object detection API,
The TensorFlow Object Detection API supports both TensorFlow 2 (TF2) and TensorFlow 1 (TF1). 

Documentation:https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/

Install Object Detection 
    
    $ git clone https://github.com/tensorflow/models

Inside ../models/research  

    !protoc object_detection/protos/*.proto --python_out=.

    !python -m pip install --use-feature=2020-resolver .

Test your installation

    !python object_detection/builders/model_builder_tf2_test.p



## Usage

you can download the checkpoint from the checkpoint folder directly
above ,and provide the path of the paricular checkpoint so that you can restore

Download the model:

    !wget http://download.tensorflow.org/models/object_detection/tf2/20200711/ssd_resnet50_v1_fpn_640x640_coco17_tpu-8.tar.gz

Extract:

    !tar -xvf ssd_resnet101_v1_fpn_640x640_coco17_tpu-8.tar.gz    

run the cells of

     helmet_detection.ipynb 

     





## Test

The model has been tested on two videos mentioned below

Test video link(Easy):https://www.youtube.com/watch?v=9WNzIDEcNP4

Test video link(Hard):https://www.youtube.com/watch?v=iEIk3RpV6RA
 