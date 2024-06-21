# Machine Learning C241-PS504

# Trashub-ML
This document contains a comprehensive approach to building a Machine Learning project that is a waste type image classification system.

## Table of Contents
* [Introduction](#Introduction)
* [Dataset](#Dataset)
* [Model Architecture](#Model-Architecture)
* [Model Demo](#Model-Demo)
* [Training](#Training)
* [Evaluation](#Evaluation)

## Introduction
Project Trashub, which is an app that focuses on developing a mobile application to identify types of waste and provide relevant information regarding their processing. Through this application, users can better utilize waste around them to create other useful products.

## Dataset
* [Sampah](https://drive.google.com/file/d/1Q4M-0MDU9ji7nB4H36InilMEyLLTgS-P/view?usp=sharing)

For the image classification of waste types, we have a total of 12 classes:
+ cardboard
+ clothes
+ electronics
+ food waste
+ glass
+ leaf waste
+ metal
+ paper
+ plastic
+ shoes
+ trash
+ wood waste

## Model Architecture
### Trash Image Classification
Transfer learning is used in this project, where the pre-trained MobileNet model serves as the foundation for trash classification. After being trained and rigorously evaluated, this model achieves good accuracy on the validation dataset.

## Model Demo
The demo for our model, you can access in this link : [Model Demo](https://colab.research.google.com/drive/1nHUX531tq7lhN_0uSOleKdwt7onhmxyc?usp=sharing)

## Training
The training process is carefully detailed to ensure reproducibility and high performance. The trash classification model uses transfer learning with the MobileNet architecture, which has been modified for this specific task. The model leverages feature engineering and TF-IDF vectorization to classify different types of trash based on images.

## Evaluation
Evaluation of the models is conducted using standard metrics to ensure they meet the expected performance standards. For the trash classification model, accuracy metrics are used to determine the model's performance on the validation dataset. The training process is documented with accuracy and loss values for each epoch, showing the model's improvement over time. The final model achieved a validation accuracy of 95.49%, demonstrating its effectiveness in classifying different types of trash.
