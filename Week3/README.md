# DTSA5511 Week 3 Project
This is the public repository for the week 3 Mini Kaggle Competition Project.

**Table of Contents**

## What's included
In this GIT repository, you will find the following items:
1. [weatherAUS.csv](weatherAUS.csv) is the csv file that is downloaded from Kaggle. 
Retrieved from [https://www.kaggle.com/datasets/ahmettalhabektas/new-york-cars-big-data-2023](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package), Apr. 30, 2024.

2. [DTSA_5511_Final_Project_DF.ipynb](DTSA_5511_Final_Project_DF.ipynb) is the jupyter notebook of this project.

## Project Summary
In this project, the aim is to build a Convolution Neural Network Algorithm to identify the metastatic cancer in small image subsets from larger digital pathological scans. 
The dataset come from Kaggle Competition [https://www.kaggle.com/competitions/histopathologic-cancer-detection/overview]. The dataset consists of RGB .tif images with dimensions of 96 by 96 pixels. Each training image has been assigned a label of 0 (benign) or 1 (cancerous). There are 220025 training images, 130908 with label of 0 and 89117 with label of 1. I will use 85% for training and 15% for validation. For the CNN model build and training process, I will be using `tensorflow.keras` [https://www.tensorflow.org/guide/keras].

