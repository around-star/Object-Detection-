# Object Recognition
Using the Faster RCNN architecture from tfhub.


## Faster RCNN
[Paper](https://arxiv.org/pdf/1506.01497.pdf)

Faster RCNN is a **two step** object detection algorithm, where it makes use of the **region proposal networks** in the first stage to extract the ROIs and performs classification and regression to output the corresponding class and the coordinates of the region in the second stage. It uses **anchor boxes** (predefined boxes of varying scale and aspect ratios obtained on running clustering algortithm on real boxes) which is useful in cases where a two different objects share the same centre.
