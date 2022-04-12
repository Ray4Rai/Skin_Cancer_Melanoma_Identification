# Skin Cancer Melanoma Identification

## Overview:
Skin cancer is the most prevalent type of cancer. Melanoma, specifically, is responsible for 75% of skin cancer deaths, despite being the least common skin cancer. As with other cancers, early and accurate detection—potentially aided by data science—can make treatment more effective. Melanoma is a deadly disease, but if caught early, most melanomas can be cured with minor surgery. Thus, Better detection of melanoma has the opportunity to positively impact millions of people. 
## Challenge Description:
The task was to identify melanoma in images of skin lesions. In particular, I used images within the same patient and determine which are likely to represent a melanoma. Using patient-level contextual information may help the development of image analysis tools, which could better support clinical dermatologists. Dermatologists could enhance their diagnostic accuracy if detection algorithms could perform well. If successful, classifiers would be more accurate and could better support dermatological clinic work. Competition was conducted on Kaggle. [link](https://www.kaggle.com/c/siim-isic-melanoma-classification/overview)
## My Solution:
**A Deep-Learning model to identify Melanoma in lesion images to detect Skin Cancer.**<br> The model took account of "contextual" images within the same patient to determine which images represent a melanoma. Along with the application of Computer-Vision to extract information from the lesion images, the model also used the meta data information of the patients like sex and age to extract some more information. The tabular data was feature-engineered for the best use to the model. SIIM-ISIC 2020 dataset was used for model training. 
## Performance:
The model achieved **0.9398 ROC-AUC score**.
## Repo Description:
The repository contains both:
- **The models** in ipynb format in the **notebooks** folder. 
- the csv files in the **submission_csv_files** folder which are few of the submissions made to the competitions. NOT MUCH OF USE, these were added to the repo just to archieve the files.
