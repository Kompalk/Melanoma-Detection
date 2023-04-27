# Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- **Dataset** : The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

  The data set contains the following diseases:

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
-  Which class has the least number of samples? - Actinic Keratosos and Seborrheic keratosis
- Which classes dominate the data in terms proportionate number of samples? -
Pigmented benign keratosis dominates the data of count more than 100 in training
-The class rebalance helped in reducing overfititng of the data and thus the loass is beng reduced But it reduced the Acurracy very low
- Initially we tried without the ImageDataGenerator which created data to over fit at high ratio
- Then we introduced dropout and ImageDataGenerator which reduced the over fit
- At last we tried Batch Normalization and Augumentation which really helped in carry forward


## Technologies Used
- numpy - version 1.21.6
- pandas - version 1.3.5
- seaborn - version 0.11.2
- matplotlib - version 3.2.2
- tensorflow - version 2.12.0
- keras - version 2.12.0
- Pillow - version 8.4.0


## Acknowledgements
Give credit here.
- This project was inspired by
    - **G.Srinivasaraghavan** - Professor, IIIT-Bangalore
    - **Gunnvant Singh Saini** - Analytics professional in EdTech
    - **Dr Avishek Pal** - Senior Data Scientist, Microsoft


## Contact
Created by [@Kompalk] - feel free to contact me!