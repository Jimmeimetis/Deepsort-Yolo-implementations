# Deepsort-Yolo-implementations

Supplementary material for our tests.This deepsort implementation has been modified to display proper confirmed tracks on the bounding boxes.Adjust n_init,IOU,Score and more as seen fit.

We provide ready to run implementations of deepsort using yolov3-tiny yolov3 and yolov4.We provide the MS-COCO weights from darknet that have been converted to keras.We also provide our own weights that we created by training these models on the UA-DETRAC dataset.These weights can only detect one class named "car" and it outperforms the MS-COCO ones.

# Introduction

  Projects that made this possible.
  
  https://github.com/AlexeyAB/darknet

  https://github.com/nwojke/deep_sort
  
  https://github.com/Qidian213/deep_sort_yolov3
  
  https://github.com/Ma-Dan/keras-yolo4

# Quick Start

1. Download weights from [our google drive](https://drive.google.com/drive/folders/1a_q-jeazMH7H-qikFGdgKrwyH_vxtUg3).

2.Place them in the model_data folder and propely link to them in the yolo.py file.Also use the correct class in the same file.

3.Download our test scenes from the same google drive or use your own.Link to them in the test.py file.

4.Run YOLO_DEEP_SORT with cmd :
   ```
   python test.py
   ```
5.Results will be shown in a new window as it processes the video and also benchmark data in the CMD window.
