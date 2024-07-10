# Melenoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma from a dataset consisting of more than 2300 images, which were formed from the International Skin Imaging Collaboration (ISIC)

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- The data set contains the following diseases:
    - Actinic keratosis
    - Basal cell carcinoma
    - Dermatofibroma
    - Melanoma
    - Nevus
    - Pigmented benign keratosis
    - Seborrheic keratosis
    - Squamous cell carcinoma
    - Vascular lesion
## Conclusions
- Model without dropout and regularization is clearly overfitting with 80% train accuracy and 42% validation accuracy
- With the addition of L2 regularization the training accuracy drops to 63% while validation accuracy improves to 50%
- Addition of dropout layers after Conv and dense layer reduced the training and validation accuracy to 30% and 36% respectively
- Class imbalance can significantly reduce the performance of model. Using Augmentor to improve balance between classes


## Technologies Used
- tensorflow - version '2.16.2'
- keras - version '3.4.1'

## Contact
Created by [@achamaria2701] - feel free to contact me!
