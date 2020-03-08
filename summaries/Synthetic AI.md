[TOC]

# Synthetic AI

Nikolenko, Sergey I. “Synthetic Data for Deep Learning.” ArXiv:1909.11512 [Cs], September 25, 2019. http://arxiv.org/abs/1909.11512.
- todo

Griffiths, David, and Jan Boehm. “1-SynthCity: A Large Scale Synthetic Point Cloud.” ArXiv:1907.04758 [Cs], July 10, 2019. http://arxiv.org/abs/1907.04758.

- present SynthCity an open dataset to help aid research. SynthCity is a 367.9M point synthetic full colour Mobile Laser Scanning point cloud. Every point is assigned a label from one of nine categories.We generate our point cloud in a typical Urban/Suburban environment using the Blensor plugin for Blender.

Handa, Ankur, Viorica Patraucean, Vijay Badrinarayanan, Simon Stent, and Roberto Cipolla. “1-Understanding Real World Indoor Scenes With Synthetic Data,” 4077–85, 2016. https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Handa_Understanding_Real_World_CVPR_2016_paper.html.

Hinterstoisser, Stefan, Vincent Lepetit, Paul Wohlhart, and Kurt Konolige. “1-On Pre-Trained Image Features and Synthetic Images for Deep Learning,” 0–0, 2018. http://openaccess.thecvf.com/content_eccv_2018_workshops/w6/html/Hinterstoisser_On_Pre-Trained_Image_Features_and_Synthetic_Images_for_Deep_Learning_ECCVW_2018_paper.html.


Wang, Fei, Yan Zhuang, Hong Gu, and Huosheng Hu. “Automatic Generation of Synthetic LiDAR Point Clouds for 3-D Data Analysis.” IEEE Transactions on Instrumentation and Measurement 68, no. 7 (July 2019): 2671–73. https://doi.org/10.1109/TIM.2019.2906416.

- presented a new method to automatically
extract 3-D LiDAR point clouds with point-level ground truth labels(**PC generation framework with labels**) from an autonomous driving simulator for 3-D data
analysis.
- 1)achieve a visible **performance boost** of a deep model; 2) **significantly reduce the amount of manually labeled data** for training; and 3) help to **avoid the data set bias problem** when real data contains limited types of scenes.


Yue, Xiangyu, Bichen Wu, Sanjit A. Seshia, Kurt Keutzer, and Alberto L. Sangiovanni-Vincentelli. “A LiDAR Point Cloud Generator: From a Virtual World to Autonomous Driving.” ArXiv:1804.00103 [Cs], March 30, 2018. http://arxiv.org/abs/1804.00103. 3 star

- proposed **a labeled PC generator framework based on a game engine**; This can be used to: 1) obtain **a large amount of annotated point cloud data**, which can then be used to help neural network training; 2) systematically test, analyze and improve performance of neural networks for tasks such as point cloud segmentation.

- synthesized data help improve the validation accuracy (IoU) by 9%; identify potential weakness/blind spots of our neural network model and fix them.

- 3 star, felt not reliable and confident since the experiments are not comprehensively conducted.