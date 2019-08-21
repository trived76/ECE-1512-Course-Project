# Semantic-Segmentation
This repository is for Digital Image Processing Course project (Team work). We wanted to explore state-of-art computer vision semantic segmentation algorithms. With images, there are three main solutions that we can tailor for any application: Image classification, Object detection and Sematic segmentation. You might have seen pixel-wise labelling of the image, yes, that is what the sematic segmentation is for! 


## Tasks:
Design a Semantic Segmentation pipeline with FCN, U-Net, ENET and CRFasRNN . (Report before 4th February 2019) for 'Semantic Segmentation for Self Driving Cars' Dataset provided as a part of Lyft Udacity Challenge. 

The dataset is available at this [link](https://www.kaggle.com/kumaresanmanickavelu/lyft-udacity-challenge).

## Pipeline:

1) The images are preprocessed with augmentation, resizing and morphological operations.
2) The 4 models are designed and trained with categorical cross entropy for 30 epochs.
3) The models are evaluated on the basis of IoU, training and prediction time, GPU Utilization.
4) Finally the the models have been implemented on a 10 sec video.

## Description of files:

1) [13-Final_Project_Code.ipynb](https://github.com/trived76/Semantic-Segmentation/blob/master/13-%20Final_Project_Code.ipynb): Contains the complete code for the 4 algorithms (KERAS implementation). It also contains the image processing pipeline 
2) [To_show_Video.mp4](https://github.com/trived76/Semantic-Segmentation/blob/master/To_show_Video.mp4): It is the video file on which we implemented pre-trained sematic segmentation models. We checked how these four different models work on the unseen dataset. It is for visual comparison.

The [cpp folder](https://github.com/trived76/Semantic-Segmentation/tree/master/cpp), [crfrnn_layer](https://github.com/trived76/Semantic-Segmentation/blob/master/crfrnn_layer.py) and [high_dim_filter_loader](https://github.com/trived76/Semantic-Segmentation/blob/master/high_dim_filter_loader.py) have been taken from the [GitHub repo of the authors of CRFasRNN](https://github.com/sadeepj/crfasrnn_keras). These files are for CRFasRNN algorithm only. 


## Contributors:

1) Maharshi Trivedi ([trived76](https://github.com/trived76))
2) Vaibhav Gupta ([vaibhavpec2012](https://github.com/vaibhavpec2012))

The content was equally assimilated and created by both the contributors. 
