# Melanoma_Assignment_Aishwarya
Repositry to store project files for a skin cancer detection project
### Team Members: Aishwarya Avinash, Nikhil Panchagnula and Shan Salance
**In this assignment, you will build a multiclass classification model using a custom convolutional neural network in tensorflow.**


## Table of contents:
•	General info
•	Technologies used
•	Conclusions
•	Acknowledgements
•	Contact
## General info:
Melanoma is a type od cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
We are provided a dataset consisting of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). The data set contains the following diseases:
1.	Actinic keratosis
2.	Basal cell carcinoma
3.	Dermatofibroma
4.	Melanoma
5.	Nevus
6.	Pigmented benign keratosis
7.	Seborrheic keratosis
8.	Squamous cell carcinoma
9.	Vascular lesion

**Link to my google drive where I kept and used my zip dataset https://drive.google.com/drive/folders/13d9icXqHbgyGDKn2wtYg-XiBhdfnzf2B?usp=drive_link**
## Technologies used (libraries and computation)
•	Google colab
•	Power of T4 GPU from colab (for execution)
•	Tensorflow (version: 2.13.0)
•	Matplotlib (version 3.7.1)
•	Pathlib (version 1.0.1)
## Conclusions:
-	Base model performed very well on train but poor in validation, which showed sign of overfitting
-	To rectify augmentation like rotation, flip and zoom were used along with drop out was used which helped with overfitting, but dropped accuracy of train and validation
-	Class imbalance was detected and hence augmentation was used to help with it and which provided the best performing model so far
## Acknowledgements:
This project was a team effort of Aishwarya Avinash_Nikhil, Panchagnula and Shan Salance. It was also guided by the notebook provided Mr. Sayan Dey, Upgrad Instructor that led us to the steps to follow and achieve the best results.
## Contact:
created by @aishwarya10397
please feel free to contact me on github :) 
