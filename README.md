# YOLOv3 + SORT

*This project is to detect and track person on a video stream and count those going through a defined line.*

## Requirement

* Python 3.5
* OpenCV
* Numpy

It uses:

* __[YOLOv3](https://github.com/yehengchen/ObjectDetection/tree/master/OneStage/yolo/yolov3)__ to detect objects on each of the video frames. - 用自己的数据训练 YOLOv3 模型

* __[SORT](https://github.com/abewley/sort)__ to track those objects over different frames.

Once the objects are detected and tracked over different frames a simple mathematical calculation is applied to count the intersections between the vehicles previous and current frame positions with a defined line.
