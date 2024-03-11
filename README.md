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

We are using a dataset from sklearn : [Go to the dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)


We have a dataset with **569** number fo instances and for the class distribution, we haev **212 malignant** & **357 benign**

We have 30 features to feat them into the classifier (= machine learning model) 

## III.Techniques used 

**Support vector machine method** to find the best line that separate the two classes 

<img src="https://github.com/I2S9/Breast-cancer/assets/111307883/49a340f2-8476-4313-b6ef-346772ca5597" width="600">

  
That best line, in this case, we are going to rely on mainly two points and these two points in our study, we're gonna call it the **supported vectors**


<img src="https://github.com/I2S9/Breast-cancer/assets/111307883/e348b9b6-f97f-4310-b4f1-577b675f81a4" width="600">

We have the maximum margin hyperplane which is the hyperplane or the line that separates mainly the two classes

In order to get this line, we used a distance what we call the maximum margin distance and that's the objective of supportive vector machine classifier is to find or maximize that maximum margin distance between the two classes. In order to do this we use these two mainly points and in this case, we call them support vectors.


### Support vectors 

Support vectors are the points that we assume that these points are kind of on the boundary or a kind of on a grey area. That means that they are not fully malignant in this case or benign in this case. It's kind of between where human or physician eyes for example might be able to detect if the cancer is malignant or benign or for example if that image is a cat or a dog. 

Support vector machines are very powerful techniques because it's a kind of an extreme algorithm, it doesn't classify : it just focus on the supportive vectors or the points on the boudary and separate them somehow 


## IV. References 

[[EN] Breast Cancer Detection | ResearchGate](https://www.researchgate.net/publication/271907638_Breast_Cancer_Detection_with_Reduced_Feature_Set)

[[EN] Breast Cancer Screenings | Cancer Reseach UK](https://www.cancerresearchuk.org/about-cancer/breast-cancer/getting-diagnosed/screening-breast)
