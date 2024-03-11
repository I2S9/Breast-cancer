# Breast cancer detection

## Introduction

Breast cancer is the most common cancer among women worldwide. Accounting for 25% of all cancer cases and affected 2.1 million people in 2015. Early diagnosis significantly increases the chances of survival. A key challenge of cancer detection is how to classify tumors into malignant or benign. 

**ML** (Machine Learning) techniques can dramatically improve the accuracy of diagonosis. 91% correct diagnosis is achieved using machine learning techniques 

**Objective of this project** : classify tumors into malignant or benign tumors usign features obtained from several cell images

## I. Cancer diagnosis procedure 


![benign](https://github.com/I2S9/Breast-cancer/assets/111307883/a8384b13-bbe0-4254-a7b0-334d18b8157d)

* FNA process who consist of extracting some of the cells out of the tumor, at this stage we don't know if that tumor is malignant ou benign

* The malignant (= cancerous, we need to intervene) tumor it matches the image at the top and the benign ( = tumor is kind of not spreading accross the body, the patient is safe somehow) tumor, at the image below

* As we extracted all the images and we wantes to specify if that cancer out of these images is malignant or benign

* features means some of the caracteristics of the image such as radius, for example of the cells, texture, perimeter area, smoothness and so one and then we feat all of the features for our machine learning model


## II. Dataset in Machine Learning terms 


![img2](https://github.com/I2S9/Breast-cancer/assets/111307883/f22cd9f1-fc29-4fe5-8f69-bacc01c7be8d)

We have a dataset with **569** number fo instances and for the class distribution, we haev **212 malignant** & **357 benign**

We have 30 features to feat them into the classifier (= machine learning model) 

## Techniques used 

**Support vector machine method** to find the best line that separate the two classes 

![image](https://github.com/I2S9/Breast-cancer/assets/111307883/49a340f2-8476-4313-b6ef-346772ca5597)

## References 

[[EN] Breast Cancer Detection | ResearchGate](https://www.researchgate.net/publication/271907638_Breast_Cancer_Detection_with_Reduced_Feature_Set)
