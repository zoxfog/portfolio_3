# Project Portfolio
### MSc. Projects
---
### 1. Open Set Recognition 


key methods: Supervised and unsupervised learning, image classification, CNN.
- This project focuses on the problem of Open Set Recognition (OSR). Unlike traditional classification problems, where a model is trained and tested on the same set of classes, OSR refers to a scenario where, in addition to the known classes the classifier was trained on, additional new classes might be present during test-time. In fact, this is closely related to the problem of out-of-distribution (OOD) detection.
More concretely, in this project, we are tasked with an image classification problem on the MNIST dataset. However, our model should be able to not only correctly classify MNIST examples but also flag unseen classes during test-time as ’Unknown’. In this project we tackle this problem with multi-task CNN based AE + data augmentation for classification and GMM clustering for the latent space representation of the imgaes.

#### [**Notebook](https://github.com/zoxfog/OSR/blob/main/GMDL,_Project,.ipynb)


### 2. Multitask LSTM - AE for Reconstruction and Forecasting/classifying. 
key methods: Data reconstruction, LSTM, Auto-Encoder.
- Multitask neural networks generally include a a network with different objectives, normally expressed with a multi-loss implementation. Here we implement an LSTM, with (1)  the classification/prediction task and (2) data reconstruction task. Our report shows, that even with 2 tasks, the model can achieve high accuracy given task (1).

#### [**Report:](https://github.com/zoxfog/MSc-projects/blob/main/hw2-DL/HW%202%20-%20report.pdf)
#### [**code:](https://github.com/zoxfog/MSc-projects/tree/main/hw2-DL)

### 2. Neural Network From Scratch. 
In this project we implement a fully-connected and a residual neural network using Numpy alone. Thus, all gradients, their computation ,and SGD etc are implemented with numpy. note, this project was created before the introduction of ChatGPT. Therefore a strong mathemtical understanding of NN was required for its completion

#### [**Report + code:](https://github.com/zoxfog/MSc-projects/blob/main/DL%20-hm1/Home%20Assignment%201%20(3).pdf)

### BSc. Projects
---
### 1. Day Trading Strategy Analysis (Workshop in Data Science) 
In depth analysis of my day trading strategy covering data from dozens of trades with real money. The data features many variables in addition to Entry/Exit stock prices in order to get a better picture and support future desicions. Used necessary data down to the 1-minute open, close, high, low and volume bars to retrieve better insight and accuracy.


#### [**Raw Data Extraction:](https://nbviewer.jupyter.org/github/zoxfog/Day-Trading-Analysis-2/blob/main/Raw_Data_Extraction.ipynb) 
Retrieve 1-minute, 1 day and 1 hour stock data from Interactive Brokers and Yahoo Finance, and store the new data locally. This procedure was implemented on a daily basis. 
#### [**Main Notebook:](https://nbviewer.org/github/zoxfog/Day-Trading-Analysis-2/blob/e36a20c2cb53c4e91430cc714308178c423f64e6/main.ipynb)
The main notebook of the project, here we will conduct all of the pre processing, feature engineering, exploratory data analysis, modeling and algorithmic design.


Programming Language: Python


### 2. Cardiovascular Diseases Analysis and Survivability Prediction (Data Mining) 

Analysis of a dataset of 299 patients with heart failure collected in 2015. Prediction and cluster analysis of patient survivability based on 13 attributes.

#### [**Project Notebook](https://nbviewer.jupyter.org/github/zoxfog/Cardiovascular-Diseases/blob/main/Cardiovascular%20Diseases.ipynb)


Programming Language: Python



