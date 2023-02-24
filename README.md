
# Head Pose Estimation using AFLW2000-3D Dataset

## Introduction
This is a project for estimating the 2D head pose (pitch, yaw, and roll) of a person in an image using the AFLW2000-3D dataset. The AFLW2000-3D dataset contains 2000 faces with 21 3D landmarks per face. We used only the 2D images and their corresponding 3D landmark annotations to train a machine learning algorithm for predicting the head pose.

## Requirements
- Python 3.6 or later
- NumPy
- OpenCV
- Scikit-learn
- Scipy
- pandas 
- mediapipe
- matplotlib
- seaborn 

## Dataset Preprocessing
We used the 3D landmarks provided by the AFLW2000-3D dataset to calculate the pitch, yaw, and roll angles. To prepare the data for training, we centered the 2D landmarks around the nose and normalized the distances to the top of head to have unit length.

## Model Architecture
We used a support vector regression (SVR) model to predict the pitch, yaw, and roll angles. We used the radial basis function (RBF) kernel with default parameters.



## output


![download](https://user-images.githubusercontent.com/57260853/220854064-1e258a2f-9ca8-4980-b9bb-2cc8cea24af9.png)


![output](https://user-images.githubusercontent.com/57260853/220856591-6e91ec6d-a61c-426e-8391-758a080a60f7.gif)







![output2](https://user-images.githubusercontent.com/57260853/220857359-e4461fac-cad6-4307-98fd-778af52a3d9e.gif)


