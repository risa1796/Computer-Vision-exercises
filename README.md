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

coming soon ...




-------------

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Frisa1796%2FComputer-Vision-exercises&count_bg=%23EFD108&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
