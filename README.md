# Violence detection project

The goal of the project is to detect violence in video and,  identifying objects through computer vision.


## DataSet

The dataset contains videos from the kaggle site, The videos are divided into  violent videos, and  non-violent videos.

## Pipeline

The input and process 20 video frames in batch with the VGG19 model 

These transfer values were used as input to the LSTM neural network. I then trained the second neural network using the classes from the violence dataset (Violence, No-Violence), so the network learns how to classify images based on the transfer-values from the VGG16 model.
