# LUNA-Challenge



LUNA (LUng Nodule Analysis) 16 - ISBI 2016 Challenge

https://luna16.grand-challenge.org/

The model is based on the book Deep Learning with PyTorch, (https://www.manning.com/books/deep-learning-with-pytorch)



## End to End Model 

![](./imgs/1.png)



### Sample CT Scan with (I,R,C) coordinates



![2](.\imgs\2.png)



## U-Net Architecture for Segmentation

![6](.\imgs\6.png)



#### Sample result from segmentation identifying a positive nodule

![7](.\imgs\7.png)



## Resnet model for classification

![3](.\imgs\3.png)



#### Data augmentation techniques for balanced dataset

![5](.\imgs\5.png)



### A CT segment

![8](.\imgs\8.png)



### ROC Curve for final classifier with last layer fine tuned

![9](.\imgs\9.png)