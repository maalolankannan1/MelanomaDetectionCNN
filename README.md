# Melanoma Cancer Detection
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
This is a problem which is solved using Vanilla CNN architecture. There are usages of augmentations and multiple trainings to arrive at a good model.
- What is the background of your project?
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. It is important to detect it in a more automatic fashion to aid the doctors.
- What is the business probem that your project is trying to solve?
A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the dataset that is being used?
The dataset being used is the ISIC (The International Skin Imaging Collaboration) Skin Cancer Detection images set. These are divided into 9 categories and stored inside each directory named with the label name.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Since the dataset is quite small and imbalanced, directly using vanilla cnn models yielded poor results.
- Thus there was a need to augment and balance the dataset by adding new augmented images in the training set.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow
- keras
- matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by different examples that were provided in the Upgrad course content


## Contact
Created by [@maalolankannan1] - feel free to contact me!