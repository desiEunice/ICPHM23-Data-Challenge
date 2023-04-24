# ICPHM23-Data-Challenge

Author: Eunice Ofori-Addo

## Introduction
This project involves in participating in the IEEE Conference on Prognostics and Health Management (ICPHM) 2023 data challenge on vibration signal analysis for health monitoring of industrial systems.

Industrial systems are susceptible to defects and failures. To mitigate the risk of failures, reduce the likelihood of machine downtime in industrial systems, and improve their reliability, a machine learning model for effective fault detection in industrial machinery is proposed. This model uses the one-dimensional convolutional neural network (1D-CNN) on vibration signals data for classification of the fault conditions.

## Data Description
The ICPHM’23 benchmark vibration dataset was provided for this data challenge. The dataset includes vibration signals from normal and four different types of fault conditions and their corresponding ground truth labels. The four fault conditions are surface wear, crack, chipped and missing tooth. Data is provided for two different operational condition: 1500-rpm motor speed and 10Nm load and 2700-rpm motor speed and 25Nm load. My work uses only the x-direction of vibration dataset with window size of 200. Dataset consists of 50,000 samples.


## Proposed Model Architecture
The 1D-CNN architecture and parameter settings were obtained after several experiments. This 1D-CNN model architecture is a variant of the model structure proposed by Chen, Chih-Cheng, et al. in their paper “An improved fault diagnosis using 1D-CNN model”. The architecture of my model comprises of five convolutional layers with decreasing kernel size, four pooling layers and two fully connected layers.

## Results
After the results of the data challenge were announced, the proposed model was found to have a 98.283% accuracy on the test data provided.
