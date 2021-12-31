---
layout:     post
title:      Data analysis and machine learning
subtitle:   
date:       2020-10-30
author:     Zihao Wang
header-img: img/post-bg-desk.jpg
catalog: true
tags:
    - 
---

## Detecting patients with breast tumors based on circular RNAs

>University of Saskatchewan, Fall 2021

Precise detection of the amount of breast tumor-related circular RNAs (circRNAs) is vital for breast tumor diagnosis and therapy However, there is little knowledge about circRNA biomarkers related to breast tumors. In this paper, we introduced a method to
select 6480 circRNAs that relates to breast tumor among 24,409 circRNAs. To verify the diagnosis performance of selected circRNAs, a 1D convolutional neural network (1D-CNN) model is implemented and input expression data of selected circRNAs to classify people with non-tumor and tumor. The model was trained and tested based on 114 people without tumors and 1135 people with tumors. It achieved an excellent classification accuracy of 93%. This result
demonstrates selected circRNAs can be used to diagnose breast tumors.

![](https://github.com/wangzh3/wangzh3.github.io/blob/master/upload/data%20analysis/cRNA.png?raw=true)

The soruce code is [here](https://github.com/wangzh3/Detecting-patients-with-breast-tumors-based-on-circular-RNAs/tree/main/code) and the paper is [here](https://github.com/wangzh3/Detecting-patients-with-breast-tumors-based-on-circular-RNAs/blob/main/Detecting%20patients%20with%20breast%20tumors%20based%20on%20circular%20RNAs.pdf).

## Analysis and prediction of user behavior based on web log

The feature clustering algorithm based on similarity and the fuzzy analysis method based on rough set were used. A method of analysis and prediction of user behavior based on web log was proposed. Firstly, a standard character eigenvector library was constructed．Then，a character clustering algorithm based on cosine similarity was used for character analysis. Finally, a fuzzy analysis algorithm based on rough set theory was used to perform behavior prediction. Results showed that the method accurately analyze the personality characteristics of users and predict their future behaviors, and identify the groups that might pose a threat to the security field.

>Granted 1 invention patent, published 2 papers, directed by Professor Dr. Haiyan Kang.

Papers:<br>
[1]	Kang. H, Wang. Z, Yu. A and Tan. Y. Analysis and Prediction of User Behavior Based on Web Log. Journal of   Zhengzhou University, 51(3): 13-20, 2019.<br>
[2]	Wang. Z. Analysis and Prediction of User Behavior Based on Web Log. Bachelor thesis directed by Professor Kang Haiyan (Kang H.), Beijing Information Science and  Technology University, 2018.

Patents:<br>
[1]	Kang. H, Wang. Z. Method and system of user behavior description and prediction based on web log[P]. China, CN109783460A. 2019-05-21.

The research paper is [here](https://github.com/wangzh3/wangzh3.github.io/blob/master/upload/Paper/Analysis%20and%20Prediction%20of%20User%20Behavior%20Based%20on%20Web%20Log.pdf). The English abstract is located in the bottom of the paper.

The invention patent is [here](https://github.com/wangzh3/wangzh3.github.io/blob/master/upload/Paper/Invention%20Title%20--%20User%20behavior%20depicting%20and%20predicting%20method%20and%20system%20based%20on%20web%20log.pdf).

The interface of the system is showed below.

![](https://raw.githubusercontent.com/wangzh3/wangzh3.github.io/master/upload/data%20analysis/log.jpg)

## Using Machine Learning Techniques to Predict Potential Customers and Their Purchasing Items
> The research was supervised by Professor Dr. Sevim Oztimurlenk and Ling Zhu at the Long Island University.

The need has increased in B2C e-commerce for a more accurate recommendation system that targets customers. The system should be able to provide customers targeted purchase information based on their online behavior. A powerful and meaningful recommendation system can offer enormous value to customers and e-commerce providers. Customers can locate an item of their interest more easily and quickly. On the other hand, an e-commerce provider can achieve a higher customer conversion rate and thus increase sales. To this end this research developed a two-step machine-learning-based recommendation prototype with two data mining goals: to identify potential customers with purchase intention and to predict the products they may purchase based on an e-commerce log (i.e., a sequential record of products click-through events). In the first module, we used both the K-nearest neighbor (KNN) model and the multi-layer perceptron (MLP) neural network to classify customers with and without purchase intention. In the second module, we developed a first-order Markov chain model to predict products that those potential customers will purchase. We then tested the prototype with the dataset provided in the RecSys 2015 challenge. The results show that in the first module both the KNN and the MLP neural network have their own advantages and disadvantages in identifying those potential customers. In the second module the Markov model also performs well to predict the products purchased by a customer. The findings show that the prototype has a great potential to be developed into a machine-learning-based recommendation system for e-commerce usage. To our knowledge, this prototype is the first of its kind to combine a classification model with time series analysis.

The source code is [here](https://github.com/wangzh3/Using-Machine-Learning-Techniques-to-Predict-Potential-Customers-and-Their-Purchasing-Items).

## User emotion analysis and depression recognition system based on human-computer interaction

>The research (Master’s thesis) was supervised by Professor Dr. Liang Liang at the University of Miami.

The development of graphic human-computer interaction (HCI) agents has enabled an explosive need for user experiences satisfaction. In many HCI systems, The general architecture includes 2 parts. One was a real-time multimodal agent of human-computer interaction, which was used to enhance user experiences while interacting with the computer. Another was the voice feedback agent. Analysis of user experiences is an important research topic of HCI. users’ emotions and depression analysis is the most important and challenging problem in user experience analysis.

To solve this challenge, in this research, we proposed some machine learning approaches to achieve promising performance in analyzing user depression based on the HCI videos. Specifically, we proposed 2 directions of depression analysis. The first one is using continuous 3-dimension emotion representation (arousal, dominance and valence) combining with the Long Short-term Memory neural network (LSTM). The second one is using discrete emotion features combining with the LSTM and k-nearest neighbor (KNN) classifier. The research includes 3 parts: first, implement a facial expression recognition system based on the VGG19 neural network to recognize facial emotion in each HCI video frame. Second, generating a length of 512 feature vector of each face in each frame by using the middle output layer of VGG19. Third, using machine learning methods to predict the depression level based on the 3-dimension emotion representation and discrete emotion features. 

All the proposed machine learning techniques are trained and evaluated based on the Audio-Visual Emotion recognition Challenge (AVEC) 2014 dataset. The experimental results show the most effective method is the K nearest neighbor (KNN) based on the discrete emotion feature. The accuracy reaches 70% and the recall for non-depression detection reaches 96.8% which is higher than the baseline 85.9%. The result illustrates it’s a promising performance and could be applied to real-world applications.

The thesis and the source code are available [here](https://github.com/wangzh3/USER-EMOTION-ANALYSIS-AND-DEPRESSION-RECOGNITION-SYSTEM-BASED-ON-HUMAN-COMPUTER-INTERACTION/blob/master/Zihao%20Wang%20csc794%20final%20report.pdf).

The process of this research is illustrated in the blueprint below.

![](https://raw.githubusercontent.com/wangzh3/wangzh3.github.io/master/upload/data%20analysis/master.png)


## Human emotion recognition based on facial expression

>The research was supervised by Professor Dr. Liang Liang at the University of Miami.

This research proposes a method for training convolutional neural networks for human facial expression image classification. The trained networks may be used for human emotions analysis in many applications,such as ensuringsafe driving and human-computer interaction. Commonly, a neural network can be trained by using whole face images. However, face outline can influence emotion recognition. Since the face outline can influence the emotion feature extraction. As a solution to this problem, we proposed to train a network on the key points of facial images. The average classification accuracy of the network is 33% (7 emotion classes), which shows it is a promising method.

Paper and the source code are available [here](https://github.com/wangzh3/facial-emotion-recognition/blob/master/Human%20emotion%20recognition%20based%20on%20facial%20expression.pdf).

The figures of key points of extraction facial images are showd below.

![](https://raw.githubusercontent.com/wangzh3/wangzh3.github.io/master/upload/data%20analysis/facial%20emo.jpg)
![](https://raw.githubusercontent.com/wangzh3/wangzh3.github.io/master/upload/data%20analysis/facial%20emotion.jpg)