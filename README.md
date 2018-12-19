
Udacity-ML-capstone
This github repo contains my final project for Udacity's Machine Learning Nanodegree.
The goal of the challenge is to develop image analysis tools to enable the automated diagnosis of melanoma from dermoscopic images. The main objective is to design an algorithm that can visually diagnose melanoma, the deadliest form of skin cancer. Our algorithm will distinguish this malignant skin tumor from two types of benign lesions (nevi and seborrheic keratoses). The data and objective are pulled from the 2017 ISIC Challenge on Skin Lesion Analysis Towards Melanoma Detection. As part of the challenge, participants were tasked to design an algorithm to diagnose skin lesion images as one of three different skin diseases (melanoma, nevus, or seborrheic keratosis). In this project, we will create a model to generate our own predictions.
Datasets and Input
The data is pulled from the 2017 ISIC Challenge on Skin Lesion Analysis Towards Melanoma Detection of International Skin Imaging Collaboration.
Initial Datasets were downloaded from the Udacity repository by following below steps:-
1.	Clone the repository and create a data/ folder to hold the dataset of skin images.
2.	git clone https://github.com/udacity/dermatologist-ai.git
3.	mkdir data; cd data
4.	Create folders to hold the training, validation, and test images.
5.	mkdir train; mkdir valid; mkdir test
6.	Download and unzip the training data (5.3 GB).
7.	Download and unzip the validation data (824.5 MB).
8.	Download and unzip the test data (5.1 GB).
9.	Place the training, validation, and test images in the data/ folder, at data/train/, data/valid/, and data/test/, respectively. Each folder should contain three sub-folders (melanoma/, nevus/, seborrheic_keratosis/), each containing representative images from one of the three image classes.



