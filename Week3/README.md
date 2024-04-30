# DTSA5511 Week 3 Project
This is the public repository for the week 3 Mini Kaggle Competition Project.

**Table of Contents**

## What's included
In this GIT repository, you will find the following items:

1. [DTSA_5511_week3.ipynb](DTSA_5511_week3.ipynb) is the jupyter notebook of this project.
2. [CNN_prediction_submission.csv](CNN_prediction_submission.csv) is the output prediction submission .csv consisting of image 'id' and 'label' that has been submitted to the Kaggle Competition.
3. [week3_submission_Kaggle_score.png](week3_submission_Kaggle_score.png) is the screenshot of the Kaggle public and private score.


## Project Summary
In this project, the aim is to build a Convolution Neural Network Algorithm to identify the metastatic cancer in small image subsets from larger digital pathological scans. 
The dataset come from Kaggle Competition [https://www.kaggle.com/competitions/histopathologic-cancer-detection/overview]. The dataset consists of RGB .tif images with dimensions of 96 by 96 pixels. Each training image has been assigned a label of 0 (benign) or 1 (cancerous). There are 220025 training images, 130908 with label of 0 and 89117 with label of 1. I will use 85% for training and 15% for validation. For the CNN model build and training process, I will be using `tensorflow.keras` [https://www.tensorflow.org/guide/keras].

