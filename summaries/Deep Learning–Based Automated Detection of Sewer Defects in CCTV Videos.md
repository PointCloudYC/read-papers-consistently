##### [18-10-05] [paper11]
Deep Learning–Based Automated Detection of Sewer Defects in CCTV Videos [pdf] [code] [pdf with comments] [comments]
*Kumar Srinath Shiv, Wang Mingzhu, Abraham Dulcy M., Jahanshahi Mohammad R., Iseley Tom, and Cheng Jack C. P.*
` October 25, 2019 [automated defect detection]`

****

### General comments on paper quality
- None

### Paper overview

- bg; CCTV inspection videos can aid the sewer condition assessment.

- proposal;**presents a deep learning–based framework for the classification and localization of sewer defects**. 3 pop NNs involving SSD, YOLO, Faster R-CNN are used to experiment and evaluat on the sewer pipe defection data set.

- how; 1)data; 3800 annotated images of defects, 8 classes, and **the data set is split evenly over train,val, test set(check Table 1 of the paper)**. 2)the framework(real-time detection); 3)assert that the prototype system detected 51 out of 56 instances of
defects and generated four false positives.

- core components of the proposal; 1) data preparation; 2) the 3 NNs for detection. 3) analysis and visualization. 

### Comments

- A key issue for this paper is to prepare a high-quality labeled data set and
- split the data set evenly to ensure the model can generalize well w/o emphasis on any single category of objects.
