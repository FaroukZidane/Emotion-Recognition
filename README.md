# Facial Emotion Recognition using VGGNet-based Convolutional Neural Network

------

## Introduction

This projects implements a Real-time Facial Emotion Recognition using VGG-like Convolutional Neural Network trained on the FER2013 Dataset.

## Training

The model was trained on the FER2013 Dataset. The Kaggle Emotion and Facial Expression Recognition challenge training dataset consists of 28,709 images, each of which are 48 × 48 grayscale images.

- The Dataset

  This facial expression dataset is called the FER13 dataset and can be found at the official Kaggle
  competition page.
  ![](https://github.com/FaroukZidane/Emotion-Recognition/raw/master/docs/images/fer2013.png)

- The Network

The network implemented to recognize various emotions and facial expressions is
inspired by the family of VGG networks.

![](https://github.com/FaroukZidane/Emotion-Recognition/raw/master/docs/images/VGGnet.png)



## Prediction

- ### Prediction from a live web-cam stream:

**Open up a terminal in the project directory and run the following after reading and applying the instructions below:**

```
$ workon "VIRTUAL_ENV_NAME"
$ python PATH_TO_DIR/emotion_detector.py --cascade PATH_TO_DIR/haarcascade_frontalface_default.xml
--model PATH_TO_DIR/checkpoints/epoch_75.hdf5
```

1. workon "VIRTUAL_ENV_NAME" replace it with your own virtual environment name (if you have).
2. remove PATH_TO_DIR and add your own path of the TFOD API



