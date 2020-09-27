# [PYTORCH] Deeplab

## Introduction

Pytorch implementation of the model described in the paper **DeepLab: Semantic resultss Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs** [paper](https://arxiv.org/abs/1606.00915). 



## Datasets:

I used 2 different datases: VOC2012 and VOCaugmented (VOC2007 + 2012) Statistics of datasets I used for experiments is shown below

| Dataset                | #Classes | #Train resultsss | #Validation resultsss |
|------------------------|:----------:|:---------------:|:--------------------:|
| VOC2012                |    20    |      5011     |        1449        |
| VOCaugmented           |    20    |      1464     |        1449        |



## Training

* Using Valohai platform
* Valohai platform overview
![graph](/results/valohai_g.png)


## Experiments:

I trained models in Valohai platform using CSC Cluster. The model version control show in the picture. For each run Valohai save the results, export log, metadata and model to CSC Cloud storage

![valohai](results/valohai.png)
- **VOC2012**
![voc2012 loss](results/voc2012_loss.png)
- **VOCaugmented**
![vocaugmented loss](results/vocaugmented_loss.png)

## resultss

Some output predictions for experiments for each dataset are shown below:

- **VOC2012**

<img src="results/voc2012_1.jpg" width="300">  <img src="results/voc2012_1_prediction.jpg" width="300">
<img src="results/voc2012_2.jpg" width="300">  <img src="results/voc2012_2_prediction.jpg" width="300">
<img src="results/voc2012_3.jpg" width="300">  <img src="results/voc2012_3_prediction.jpg" width="300">

- **VOCaugmented**

<img src="results/vocaugmented_1.jpg" width="300">  <img src="results/vocaugmented_1_prediction.jpg" width="300">
<img src="results/vocaugmented_2.jpg" width="300">  <img src="results/vocaugmented_2_prediction.jpg" width="300">
<img src="results/vocaugmented_3.jpg" width="300">  <img src="results/vocaugmented_3_prediction.jpg" width="300">
