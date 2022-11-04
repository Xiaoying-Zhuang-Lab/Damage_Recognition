# Damage_Recognition

This study aims to develop an approach to automatically recognize post-earthquake structural damage using convolutional neural networks (CNNs). 

## Stratified_KFold/Stratified-KFold-cross-validation-main/

First, the proposed method is developed using transfer learning (feature extraction and fine-tuning) with a pre-trained MobileNet model on a small dataset of 2000 images. 
The MobileNet model is trained and tested by 5-fold cross-validation. 

## Bayersian/Bayersian-main/

Second, the Bayesian optimization method and the fine-tuning strategy are used to find the relative optimal hyperparameters of the MobileNet model. 

## Grad_CAM-main/

Third, gradient-weighted class activation mapping (Grad-CAM) is used to produce a coarse localization map that highlighted crucial regions on structural damage images. 

## than.github.io-master

Final, the MobileNet model with relative optimal hyperparameters is further developed as a user-interactive web application to rapidly identify structural damage caused by earthquakes. 
