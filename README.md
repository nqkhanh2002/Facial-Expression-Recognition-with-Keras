<a name="readme-top"></a>
<div align="center">
  <p align="center">
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/nqkhanh2002/Facial-Expression-Recognition-with-Keras/issues">Report Bug</a>
    ·
    <a href="https://github.com/nqkhanh2002/Facial-Expression-Recognition-with-Keras/issues">Request Feature</a>
  </p>
</div>

<h1 align="center"> Facial Expression Recognition </h1>

<img src="https://miro.medium.com/max/1400/1*cQMgkngnYdIRHcZ2cJUnAg.jpeg"> <br>
## About The Project
In this work, I will build and train a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). I will use OpenCV to automatically detect faces in images and draw bounding boxes around them. Once you have trained, saved, and exported the CNN, I will directly serve the trained model predictions to a web interface and perform real-time facial expression recognition on video and image data.

##  Dataset
Dataset from [kaggle competition](https://www.kaggle.com/datasets/debanga/facial-expression-recognition-challenge).
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

## Objectives
1. Develop a facial expression recognition model in Keras

2. Build and train a convolutional neural network (CNN)

3. Deploy the trained model to a web interface with Flask

4. Apply the model to real-time video streams and image data

## Installation
1. Clone the repo
    ```sh
   https://github.com/nqkhanh2002/Classify-Traffic-Signs-Using-Deep-Learning-for-Self-Driving-Cars.git
   ```
2. Run the jupyter notebook 
    Notebook will automatically download data to your device. During notebook execution, use [the package installer for Python](https://pypi.org/project/pip/) to install packages that you are missing.
3. Edit parameter VideoCapture in [camera.py](https://github.com/nqkhanh2002/Facial-Expression-Recognition-with-Keras/blob/master/camera.py) to specific your video source. Edit any video in [videos folder](https://github.com/nqkhanh2002/Facial-Expression-Recognition-with-Keras/tree/master/videos) that you want to apply the model.
4. Run file [main.py](https://github.com/nqkhanh2002/Facial-Expression-Recognition-with-Keras/blob/master/main.py) to apply the model to real-time video streams and image data

## Contact 
* Facebook : [Nguyễn Quốc Khánh](https://www.facebook.com/nqk.dev)
* Email : nqkdeveloper@gmail.com
