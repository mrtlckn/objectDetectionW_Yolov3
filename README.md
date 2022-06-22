# objectDetectionW_Yolov3

<div>
  
# What is YOLOv3?
YOLOv3 (You Only Look Once, Version 3) is a real-time object detection algorithm that identifies specific objects in videos, live feeds, or images. YOLO uses features learned by a deep convolutional neural network to detect an object. Versions 1-3 of YOLO were created by Joseph Redmon and Ali Farhadi.

The first version of YOLO was created in 2016, and version 3, which is discussed extensively in this article, was made two years later in 2018. YOLOv3 is an improved version of YOLO and YOLOv2. YOLO is implemented using the Keras or OpenCV deep learning libraries.

<br> ![image](https://user-images.githubusercontent.com/83788186/174971543-fd094683-1711-4e4c-88fb-7dad23a337f1.png) </br>

<br> **How does YOLOv3 work?** </br>
YOLO is a Convolutional Neural Network (CNN) for performing object detection in real-time. YOLO has the advantage of being much faster than other networks and still maintains accuracy.

<br> ![image](https://user-images.githubusercontent.com/83788186/174971806-e6d69e33-4bf4-4c2f-904a-3304baf5c870.png) </br>

<br> You can learn more about YOLOv3 : https://viso.ai/deep-learning/yolov3-overview/ </br>
</div>

<div>
  
 # Coco Dataset
  
  The MS COCO (Microsoft Common Objects in Context) dataset is a large-scale object detection, segmentation, key-point detection, and captioning dataset. The dataset consists of 328K images.
  
  Splits: The first version of MS COCO dataset was released in 2014. It contains 164K images split into training (83K), validation (41K) and test (41K) sets. In 2015 additional test set of 81K images was released, including all the previous test images and 40K new images.

Based on community feedback, in 2017 the training/validation split was changed from 83K/41K to 118K/5K. The new split uses the same images and annotations. The 2017 test set is a subset of 41K images of the 2015 test set. Additionally, the 2017 release contains a new unannotated dataset of 123K images.
  
  <br> ![image](https://user-images.githubusercontent.com/83788186/174972806-91b276b4-c658-4107-82d6-1e81f51bdb0e.png) </br>
  
  https://cocodataset.org/#home
</div>

<div>
  
 # Object Detection with YOLOv3
  
  First, I made the database available for certain objects, if algorithm detects this object from image, then crops from main image and save MySQL and pandas dataFrame some specific feature which are "Tpye, Confidences, Coordinates, filepath, Okey_or_Not, time".
  
  <br> ![image](https://user-images.githubusercontent.com/83788186/174973443-7447ab17-a306-49aa-a93b-22f6d6b25398.png)</br>
  
  **Image**
  
  <br> ![image](https://user-images.githubusercontent.com/83788186/174984106-107d5d57-15ab-46ec-8622-8462361b3755.png) </br>
  **1-Detect my object from Image**
  <br> ![image](https://user-images.githubusercontent.com/83788186/174984177-2edecff0-50a5-48a0-b654-2c00fff4eca7.png)  </br>
  
  **2-Crop my object (some cropped images)"**
  <br>![image](https://user-images.githubusercontent.com/83788186/174984601-f6b902e3-de15-4872-b951-edcf8961648c.png) </br>
  <br> ![image](https://user-images.githubusercontent.com/83788186/174985012-8e28198f-3c17-4439-9d1e-4fc440c35bc9.png) </br>
  
  **3-Save specific feature on MySQL and pandas dataFrame**
  
  
  <br> ![image](https://user-images.githubusercontent.com/83788186/174985137-93352531-575b-4201-8a81-d01d9ad7449e.png)</br>
  <br> ![image](https://user-images.githubusercontent.com/83788186/174985225-8e9ab017-0d87-4a36-96e0-7df9a06309f1.png)</br>
</div>
