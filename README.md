# Portfolio
Academic and Professional Portfolio

# Predicting Stock Trend using Machine Learning (XGBoost)

![Prediction Sample Image](https://github.com/anish-chougule/portfolio/blob/main/Stock%20Trend%20Predictor/stock_trend_prediction.png)

A simple program that learns stock trend movement through technical indicators like Relative Strength Index, Moving Averages and their differentials and predict trends on unseen data. It can be used as a usefull tool to decide long or short position for a particular stock. It can also be utilized to analyze actual value of the equity regardless of what the current price is. [Try it for your self here!](https://github.com/anish-chougule/portfolio/blob/main/Stock%20Trend%20Predictor/stock_trend_prediction.ipynb)

## Libraries Used

- Python Standard Library
- Pandas
- Numpy
- YFinance :moneybag:
- TA-Lib  :computer:
- Scikit-Learn
- XGBoost
- MatPlotLib  :chart_with_upwards_trend:

## Features

- Retrieving Historical stock prices from Yahoo Finance
- Storing and Cleaning data
- Using technical analysis library to calculate stock momentum indicators and their derivatives
- Making two machine learning models: KNN Classifier and XGBoost
- Training these models with training dataset and testing them on testing dataset
- Calculating Accuracy of predictions
- Predicting future trend using today's stock data

# Optimization of Real-time 3D Object Detection Inference in Point Clouds (Undergraduate Research)

<p float="left">
  <img src="https://github.com/anish-chougule/portfolio/blob/main/Undergraduate%20Research/Actual.jpg" width="500" height="200" />
  <img src="https://github.com/anish-chougule/portfolio/blob/main/Undergraduate%20Research/Modified.jpg" width="500" height="200" />
</p>

Object detection in LiDAR point clouds is an important application especially for autonomous driving. So far, most work has been focused to develop deep learning architectures and to improve the detection performance. However, in addition to accuracy, inference speed is a very important component to quickly detect moving objects. We present an evaluation and comparison of the inference of state-of-the-art deep learning models for LiDAR-based 3D object
detection. These models were created using the OpenPCDet library. All the experiments were performed on the KITTI benchmark dataset and
show the differences in performance between the six models:

1. PointPillars
2. SECOND
3. SECOND_IOU
4. PvRCNN
5. PointRCNN
6. PointRCNN_IOU

## Method

- Models were tested on 7481 image and point cloud pairs with available 3D bounding box annotations for three categories: Car, Pedestrian and Cyclist. Training and testing timings were measured along with their performance over various categories for all 6 models.
- The detection performance is evaluated using Average Precision (AP) in moderate level for the 3D object detection task with Intersection
over Union (IoU) thresholds of 0.7 for Car and 0.5 for Pedestrian and Cyclist.
- KITTI PointPillars configuration from the OpenPCDet codebase were used to construct and train the model.
- The experiments were performed over the Pitzer cluster, on NVIDIA Volta V100 16GB GPUs . All the dependencies were installed in a CUDA 10.2 conda environment, using PyTorch.

## Results


On average accuracy: Car(92%) > Cyclist(77%) > Pedestrian(60%)  

##

Anish Chougule  
Bachelors in Computer Science  
Youngstown State University ('23 Expected Grad)  
Proficient in Data Science, Analytics, Software and Web development  
