# Melanoma Skin Cancer Detection Assignment
> Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement
In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. The aims to shorten the current gap to just a couple of days by providing the predictive model. The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.

### Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.

The data set contains the following diseases:
0	squamous cell carcinoma	181
1	dermatofibroma	95
2	actinic keratosis	114
3	pigmented benign keratosis	462
4	nevus	357
5	vascular lesion	139
6	seborrheic keratosis	77
7	basal cell carcinoma	376
8	melanoma	438

## Conclusions
### Model Architecture
<img width="602" alt="image" src="https://github.com/rrajanml/MelanomaDetectionAssignment_rrajan/assets/99160338/bdf80c14-9375-41d8-88da-a59599c3d4eb">

### Model Evaluation
![image](https://github.com/rrajanml/MelanomaDetectionAssignment_rrajan/assets/99160338/8822b162-747b-4ce1-af94-f5c3148608b4)

Actual Class basal cell carcinoma
Predictive Class pigmented benign keratosis

![image](https://github.com/rrajanml/MelanomaDetectionAssignment_rrajan/assets/99160338/e496680e-e967-48cf-865d-759f77f08cf1)


## Technologies Used
Python (3.9)
Flask framework 
scikit-learn (1.0)
numpy
pandas
gunicorn
flask_cors
opencv-python-headless (4.5.5.64)
FuzzyWuzzy
strsimpy (0.2.1)

## Acknowledgements
- This project was done as an Assigment by Upgrad and IIIT-B.
- This project was based Melanoma Skin Cancer Detection Assignment which was part of CNNs Algorithms
- I would like to Thank my teachers & my peer-students whos supported me to complete this assignment.

## Contact
Created by Rakesh Rajan-(https://github.com/rrajanml) feel free to contact me!
