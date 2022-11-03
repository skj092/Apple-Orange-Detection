# Apple-Orange-Detection

## To Count the apples and oranges in the video frame

**[Dataset](https://www.kaggle.com/datasets/sonujha090/appleorange)**
Consist of 206 training images and 56 validation image taken from kaggle.com. Some of the images was not labelled properly so I relabeled with labelImg. 

**Modal** : YOLOV5

**Tracking**: DeepSort

Trained on google colab for 500 epoch but early epoch stopped at 461 with the following result:

|Class|mAP|
|-----|----|
|Apple|0.80|
|Orange|0.58|


**Result**

![sample](https://user-images.githubusercontent.com/43055935/199639677-f07c3aa8-702c-4340-a2ff-c73e175889d6.gif)

**Code:** https://drive.google.com/drive/folders/1c9kCoBng37zuGHNgCG89FfpaxmDN86mw?usp=sharing
