# Chest X-Ray Image Classification by using PyTorch, CNN (Pneumonia)

The dataset of my project for [Deep Learning with PyTorch:Zero to GANs](https://jovian.ai/learn/deep-learning-with-pytorch-zero-to-gans) is Chest X-Ray Image Classification (Pneumonia) which I obtained from the [Kaggle - Chest X-Ray Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).


## Context
![Example of Chest X-rays in patients](https://i.imgur.com/jZqpV51.png)

The normal chest X-ray(left panel) depicts clear lungs without any areas of abnormal opacification in the image.
Bacterical pneumonia (middle panel) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia(right panel) manifets with a more diffuse "interstitial" pattern in both lungs.

## Content

The dataset is organized into 3 folders (train, test, val) and contains subfolders of each image category (Pneumonia / Normal). There are 5,863 X-Ray images (JPEG) and 2 categories(Pneumonia/Normal)

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.


## Project Tasks
- Upload the dataset from Kaggle
- Getting the Data and seperate all data directory (train, validation, test)
- Exploratory Data Analysis
- Image Processing
  - Data Augmentation
  - Data Loaders
- Model
  - Using Pre-Trained Models for Image Classifications
  - Training the model
  - Saving and loading the model
  
  
