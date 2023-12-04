# IDCAMP 2023 - Final Submission
## Scissor Rock Paper Classification
### Overview
This image classification project aims to develop a convolutional neural network (CNN) for categorizing images based on hand shapes (scissors, rock, paper). The CNN model that implemented on this project is Keras framework, comprises convolutional and polling layers for feature extraction and a fully connected layer for classification.

### Dataset
Dataset that used on this project is public dataset. There are three data classifications namely scissor, rock, and paper which are 750, 726, and 712 items. With 2188 datas, the data is separated into training data (0.6) and validation data (0.4).
Source Data: https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip

### Result
First, training is executed with 75 epochs and resulted Figure 1. At the Figure 1, the accuracy has increased significantly until epoch 30 to 40. At the next epoch the graph becomes saturated with many spikes on the graph. 

![Figure 1](/result/graph/M75E.png "Figure 1")

To confirm whether the graph still have changes, training with 100 and 150 epochs was also carried out. In Figures 2 and 3, the graph at epochs over 75 continues to increase but is not significant and remains with many spikes.

![Figure 2](/result/graph/M100E.png "Figure 2")
![Figure 3](/result/graph/M75E.png "Figure 3")

About spikes, this can happen because the batch size is too small, the learning rate is too large, or the number of data is too small and contains a lot of outliers.
