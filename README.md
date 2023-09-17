## Computer Vision Project

# Comparison between Faster RCNN and YOLOv5

Chiara Solito and Tommaso Del Prete

## Abstract

Object detection is a subfield of computer vision that focuses on identifying and localizing objects within digital images or video frames. It involves the
development of algorithms and models that can automatically detect and classify different objects of interest in a given scene.
The goal of object detection is to not only recognize the presence of objects but also provide their precise spatial location through bounding boxes or pixel-level segmentation. This enables a more detailed understanding of the visual content and various applications such as autonomous driving, surveillance systems, image retrieval, robotics, and augmented reality use this method.\
During the project conceptualization phase, we opted to concentrate on conducting a performance analysis between two influential Object Detection algorithms, namely YOLO (specifically version 5) and Faster RCNN (with Backbone Resnet 50v2). This evaluation will be carried out on a novel, small and less-explored dataset.\
The process of annotating a substantial number of images for object detection is, in fact, both expensive and laborious. In certain instances, such as medical
applications, obtaining abundant images may even be unfeasible, we will try to understand the limitations of the two models on a small dataset, experimenting with both pre-trained and non pre-trained networks.

Our findings from comparing the two neural networks in this project will partially corroborate our initial assumptions: Faster RCNN tends to yield superior results overall, while YOLO demonstrates its speed advantage.\
Finally, it will be interesting to notice that, even if these architectures are not usually written from scratch or evaluated without pre-trained weights, Faster RCNN is able to reach satisfying results nonetheless.
