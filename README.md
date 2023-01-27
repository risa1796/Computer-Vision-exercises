# Computer Vision exercises 📸 🚀
Practice working with computer vision problems.

## 1. Binary image classification - 'Smiling or Not' with face data 

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/> 

#### [🙂🙁 not-/smiling face binary image classification ](https://github.com/risa1796/Computer-Vision-exercises/blob/main/Smile_or_Not-2.ipynb)

📝 After adjusting the parameters for image augmentation I was able to slightly improve the model performance up to validation accuracy of 98%. 
Lessons learned: My first attempt with some random parameters seemed to be not helpful for training the model properly. When i saw the first prediction result,
faces with dark pixels, especially in the mouth part, are mostly classified wrong. I deleted parameters which disturb the model training and added new parameters like adjusting brightness.. Voila! Always check some preliminary results; it is not a black-box until training the DL model itself! 


Unfortunately, the test dataset has no labels added for images. So it was unable to use the test dataset. 

Data can be downloaded from https://www.kaggle.com/datasets/chazzer/smiling-or-not-face-data

-----------

## 2. GAN model for creating abstract art 

<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=black"/> <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/> 

Before we move on to GAN model that can create new images resembling abstract art, let's have a glimpse of how a basic GAN model works. 
Here, we will use a very common dataset for ML and DL : MNIST data (Gray-scale images of digits)

[📌 Short Intro to GAN Model with MNIST data](https://github.com/risa1796/Computer-Vision-exercises/blob/main/GAN_Intro-2.ipynb)

Data for the second mini exercise can be downloaded from https://www.kaggle.com/datasets/bryanb/abstract-art-gallery

-----------

## 3. Is your sitting position good? 

<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=black"/> <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/> 

For this exercise, I started with collecting images and labeled them on my own. Good Dataset is the key! 

[🐢 거북목 AI 자가진단](https://github.com/risa1796/Computer-Vision-exercises/blob/main/Sitting_Position.ipynb)

-------------





-------------


[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Frisa1796%2FComputer-Vision-exercises&count_bg=%23EFD108&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
