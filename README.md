## Audio Source Separation Using Deep U-Net

This is the course project of EE698R(Spring Semester 2022) completed under the guidance of Prof. Vipul Arora,Dept of Electrical Engineering, IIT Kanpur. The project was created by team "Go Deep".\
The project is inspired by the works of Jansson et al. in their paper **"Singing Voice Separation With Deep U-Net Convolutional Networks"**. \
The aim of our project was to separate vocal and instrumental components of audio files using machine learning approach. We used the U-Net model proposed
in above paper for the project.\
We trained & tested the performance of U-Net model and the baseline model on **MIR-1K dataset**. We applied data augmentation techniques on MIR-1K dataset
like adding white noise and changing pitch to have a bigger and more practical audio dataset.\
We used mir_eval toolkit for evaluating our models. The evaluation metrics used were **Signal-to-Distortion Ratio(SDR), Signal-to-Interfence Ratio(SIR),
Signal-to-Artifact Ratio(SAR)**.\
The performance of our model was comparable to that of original U-Net model performance even though we used a different dataset for training and testing.
We trained both U-Net and baseline model on 3 different datasets prepared from original MIR-1K dataset. The performance of U-Net was consistently better
than that of the baseline model on all the datasets.
