# AuE893-Deep-Learning-Application-in-Engineering
AuE 8930 Course Repository

# Mini Project 1
1. Use of Numpy library
2. Use of Pandas Library

# Mini Project 2

### Problem Description
This data was collected in 1978 and each of the 506 entries represents aggregate information about homes from various suburbs located in Boston. Once you get a good fit, you can use this model to predict the monetary value of a house located at the Boston’s area. A model like this would be very valuable for a real state agent who could make use of the information provided in a dayly basis.

<img width="803" alt="image" src="https://user-images.githubusercontent.com/79803663/156498477-70623c0f-bc36-40f8-8b90-18dc1ab29891.png">

### Task 1: Read and Preprocess Data

1. Train-Test Split
2. Minmax scale

### Task 2: Shallow Neural Network

### Hyperparameters
epochs = 200
lr = 0.001
batch_size = 64
hidden_layer_size = 13
input_layer_size = 13
output_layer_size = 1


![image](https://user-images.githubusercontent.com/79803663/156498745-86d3d738-14e2-44c5-98e1-b0fadb683584.png)


### Task 3: Deep Neural Network

### Hyperparameters
epochs = 200
lr = 0.001
batch_size = 64
layer_sizes = [15, 13, 8, 1]
input_size = 13  

![image](https://user-images.githubusercontent.com/79803663/156498707-87ecd09c-2162-4d4b-b448-986bc4a35728.png)

# Mini Project 3

### Build a Convolutional Neural Network to classify objects and tune hyperparameters to optimize your model.

### Task 1: Load and Pre-Process Dataset

<img width="368" alt="image" src="https://user-images.githubusercontent.com/79803663/162352399-36d772c5-4d60-4d5b-b517-3bed54a75408.png">

### Task 2: Build Convolutional Neural Network

<img width="511" alt="image" src="https://user-images.githubusercontent.com/79803663/162352464-51eaa15e-036e-4cbf-9503-9a49b252f061.png">

### Task 3: Train Model

![image](https://user-images.githubusercontent.com/79803663/162352535-4ba02bce-93ff-4f71-9e92-1c34ee6c2df1.png)

### Task 4: Tune Hyperparameters

<img width="265" alt="image" src="https://user-images.githubusercontent.com/79803663/162352660-25919db1-6c53-41f6-83d2-5fa2b26815d4.png">

# Mini Project 4

## Build an RNN model to classify text and an LSTM model for anomaly detection (also outlier detection) on the temperature sensor data. 

### Task 1: Text Classification

This task aims to train a sentiment analysis model to classify given sentences as positive or negative, based on the Recurrent Neural Network.



### Task 2: Anomaly Detection

In manufacturing industries, the anomaly detection technique is applied to predict the abnormal activities of machines based on the data read from sensors. In machine learning and data mining, anomaly detection is the task of identifying the rare items, events, or observations that are suspicious and seem different from the majority of the data. In this task, you will predict the possible failure of the system based on the temperature data. And this failure can be detected by check if they follow the trend of the majority of the data.

The given dataset (ambient_temperature_system_failure.csv) is a part of Numenta Anomaly Benchmark (NAB) dataset, which is a novel benchmark for evaluating machine learning algorithms in anomaly detection.


