# Object_detection
Object Detection using YOLOv3

YOLOv3 is the latest variant of a popular object detection algorithm YOLO – You Only Look Once. YOLOv3 is extremely fast in comparison to other object detection algorithms and provides flexibility for tradeoff between speed and accuracy simply by changing the size of the model.

Yolo applies a single neural network to the full image. This network divides the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities.
This makes it extremely fast, more than 1000x faster than R-CNN and 100x faster than Fast R-CNN.

Refer https://pjreddie.com/media/files/papers/YOLOv3.pdf for the paper on YOLOv3
@article{yolov3,
  title={YOLOv3: An Incremental Improvement},
  author={Redmon, Joseph and Farhadi, Ali},
  journal = {arXiv},
  year={2018}
}
