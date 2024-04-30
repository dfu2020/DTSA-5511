# DTSA5511 Week 5 Project
This is the public repository for the week 4 Mini Kaggle Competition Project.

**Table of Contents**

## What's included
In this GIT repository, you will find the following items:

1. [DTSA_5511_week5.ipynb](DTSA_5511_week5.ipynb) is the jupyter notebook of this project
  
2. [week5_submission_Kaggle_score.png](week5_submission_Kaggle_score.png) is the screenshot of the Kaggle public and private score.

## Project Summary
In this week's project, we are participating in Kaggle's competition. We will build a General Adversarial Network Model (GAN) [https://en.wikipedia.org/wiki/Generative_adversarial_network]. We will be using this GAN model to transform photographs to an image that has the painting styles of Monet. 

The dataset comes from Kaggle Competition [https://www.kaggle.com/competitions/gan-getting-started]. The dataset consists the following:
1. 300 Monet painting 8-bit RGB iamges, with dimensions of 256x256 pixels.
2. 7038 photograph 8-bit RGB images, with dimensions of 256x256 pixels.
3. TFRecord dataset of the above two datasets.

The goal of this project is to Build a Generator to transform photos to Monet style paintings (and vice versa), and Discrimnator to differentiate real Monet painting images to generated Monet style painting images (or differentiate real photographs from generated photograhs).

While completing this project, I found several useful resources that helped with the understanding of the model setup and the coding process.
Jang, A., Monet CycleGAN Tutorial.[https://www.kaggle.com/code/amyjang/monet-cyclegan-tutorial]

Keras CycleGAN tutorial example. [https://keras.io/examples/generative/cyclegan/]

