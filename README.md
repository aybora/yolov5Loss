# yolov5Loss-OGAM

This work modifies original [YOLOv5](https://github.com/ultralytics/yolov5) work for hard example mining via our proposed combination of Balanced Focal Loss and Loss Rank Mining (LRM) approach. Original [loss.py](https://github.com/ultralytics/yolov5/blob/master/utils/loss.py) file is modified for LRM implementation.

Tested on YOLOv5s of [v5.0 release](https://github.com/ultralytics/yolov5/releases/tag/v5.0) and verified on YOLOv5l of [v6.0 release](https://github.com/ultralytics/yolov5/releases/tag/v6.0).

Use LRM_ignore flag for LRM activation and fl_gamma and obj flags for Balanced Focal Loss.

Related paper: http://arxiv.org/abs/2202.13080

Please consider citing our paper and YOLOv5 while using our algorithm.



