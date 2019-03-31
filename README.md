# ECE-1512-Course-Project
This repo is for Digital Image Processing Course project (Team work).


# Tasks:
Design a Semantic Segmentation pipeline with FCN, U-Net, ENET and CRFasRNN . (Report before 4th February 2019) for 'Semantic Segmentation for Self Driving Cars' Dataset provided as a part of Lyft Udacity Challenge. 

The dataset is available at this link : https://www.kaggle.com/kumaresanmanickavelu/lyft-udacity-challenge

# Pipeline

1. The images are preprocessed with augmentation, resizing and morphological operations.
2. The 4 models are designed and trained with categorical cross entropy for 30 epochs
3. The models are evaluated on the basis of IoU, training and prediction time, GPU Utilization
4. Finally the the models have been implemented on a 10 sec video

# Files:

1. 13- Final_Project_Code: Contains the complete code for thw 4 models (KERAS implementation)
2. To_show_Video: Result of application on a video

The cpp folder, crfrnn_layer and high_dim_filter_loader have been taken from the GitHub repo of the authors of CRFasRNN. They can be found at the follwoing location:  https://github.com/sadeepj/crfasrnn_keras
