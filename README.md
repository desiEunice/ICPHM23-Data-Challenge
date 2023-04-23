# ICPHM23-Data-Challenge

### Author: Eunice Ofori-Addo

## Introduction

This project involves in participating in the IEEE Conference on Prognostics and Health Management (ICPHM) 2023 data challenge on vibration signal analysis for health monitoring of industrial systems.

Industrial systems are susceptible to defects and failures. To mitigate the risk of failures, reduce the likelihood of machine downtime in industrial systems, and improve their reliability, a machine learning model for effective fault detection in industrial machinery is proposed. This model uses the one-dimensional convolutional neural network (1D-CNN) on vibration signals data for classification of the fault conditions.

## Data Description

The ICPHM’23 benchmark vibration dataset was provided for this data challenge. The dataset includes vibration signals from normal and four different types of fault conditions and their corresponding ground truth labels. The four fault conditions are surface wear, crack, chipped and missing tooth. Data is provided for two different operational condition: 1500-rpm motor speed and 10Nm load and 2700-rpm motor speed and 25Nm load. My work uses only the x-direction of vibration dataset with window size of 200. Dataset consists of 50,000 samples.
For the data preprocessing step of my work, I converted the sequence of data from its two- dimensional format to the required three-dimensional format of the CNN input layer.
