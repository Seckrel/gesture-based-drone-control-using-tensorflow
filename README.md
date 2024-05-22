# Gesture Detection for Drone Controll
___
## Abstract
The purpose of this project is to develop web-based demonstration to visualize intuitive and fluid control over 3D object using hand-based gesture controls. Project focuses on collection of data to train model, development of gesture detection model using Keras, and deployment of said model in a web app. Gesture classification is done via sequential dense neural network with three hidden layers; whereas its deployment in the form of web app is done using React JS and Three JS. End goal of project is to create a web app which can control a 3D object using hand gesture fed from webcam.
<br />
[Project Repo](https://github.com/Seckrel/personality-analyzer)

## Project Directory
```
./-|
   |-/assets (directory containing architecture of the Neural Network)
   |-/data (directory containing data used to train model)
   |-/model (directory containing froze tf graph)
```

## 🚀 To Install
```
pip install -r requirements.txt
```

## 🏁 To Run
- Run `Demo working.ipyb`

## 💽 Create New Keypoints
- Open and Run `creating keypoint csv file using media pipe.ipynb`

## 🆕 Model
- Open and Run `creating_keypoint_models.ipynb`

## References
> - D. P. Kingma and B. Jimmy, " arXiv.org," Jan 2017. [Online]. Available: https://arxiv.org/abs/1412.6980. [Accessed 03 Jan 2022].
> - M. Patrick, "mediapipe," Google LLC, [Online]. Available: https://google.github.io/mediapipe/solutions/hands. [Accessed 03 Jan 2022].
> - C. and F. , "Tensorflow," 2015. [Online]. Available: https://github.com/fchollet/keras. [Accessed 03 Jan 2022].
