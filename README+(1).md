# Melanoma_CNN_Prediction
> We will build a multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
- The class rebalance helped in reducing overfititng of the data and thus the loass is beng reduced But it reduced the Acurracy very low
- Initially we tried without the ImageDataGenerator which created data to over fit at high ratio
- Then we introduced dropout and ImageDataGenerator which reduced the over fit
- At last we tried Batch Normalization and Augumentation which really helped in carry forward

## Technologies Used
- CNN
- Batch Normalization
- Model is Sequential

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by UPGRAD under MS Program in Mahcien Learning.


## Contact
Created by [@ritesd]


<!-- You don't have to include all sections - just the one's relevant to your project -->