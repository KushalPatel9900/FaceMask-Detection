<h1 align="center">FaceMask Detection</h1>

FaceMask Detection System using Convolution Neural Networks(CNN) Python, Tensorflow, Keras, OpenCV.

## Description

This system can be used to detect mask on faces in Real-time. It can be integrated with Facecams, security Cameras, etc. Firstly, it detects the face from the frame captured by the Camera source using the HaarCascade Frontal Face Classifier and then the model predicts if there is mask on the face or not.

## Build with

- [Python](https://www.python.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [OpenCV](https://opencv.org/)
- [HaarCascade Frontal Face Classifier](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)


## Libraries involved

* __Tensorflow (1.15.0)__
* __Keras (2.3.1)__
* __Matplotlib (3.2.2)__
* __Numpy (1.19.1)__
* __OpenCV (3.4.2)__
* __Scikit-learn (0.23.1)__
* __pillow (7.2.0)__
* __imutils (0.5.3)__
* __Scipy (1.5.0)__

## Results

The model predicts the output with approximately ~95% Accuracy. The pretrained model included in the repository is trained by <code>tensorflow-gpu</code>