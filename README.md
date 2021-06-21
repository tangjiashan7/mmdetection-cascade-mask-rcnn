
Cascade-Mask-RCNN
====
Cascade Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow, based on matterport mrcnn.

This repository is based on matterport's Mask RCNN, All codes are the same as matterport except 'mrcnn/model.py', I add my cascade architecture into this file . Therefore, the usage methods are also the same as the existing Mask RCNN work , which based on matterport from GitHub or blogs.
# Introduction

MMDetection is an open source object detection toolbox based on PyTorch. It is a part of the [mmd](https://openmmlab.com/) project.

The master branch works with PyTorch 1.3+. The old v1.x branch works with PyTorch 1.1 to 1.4, but v2.0 is strongly recommended for faster speed, higher performance, better design and more friendly usage.

![](https://user-images.githubusercontent.com/55383946/122695383-cb122200-d272-11eb-8aab-7e6e8fd95004.png)

## Installation
Models are developed in Pytorch based [mmdetection](https://github.com/open-mmlab/mmdetection) 

[Learn more about READMEs](https://help.github.com/en/articles/about-readmes)
note:Pytorch 1.6.0
##description
Image analysis system

##Traning
python tools/train.py configs/cascade_rcnn_r50_fpn_1x_coco.py --gpus 1 --validate --work_dir work_dirs




## test
python tools/test.py configscascade_rcnn_r50_fpn_1x_coco.py work_dirs/your chieckpoint --out ./result/result_100.pkl --eval bbox --show


##dataset
[publaynet](https://github.com/phamquiluan/PubLayNet)
PubLayNet
PubLayNet is a large dataset of document images, of which the layout is annotated with both bounding boxes and polygonal segmentations. For more information, see [PubLayNet](https://github.com/ibm-aur-nlp/PubLayNet)


