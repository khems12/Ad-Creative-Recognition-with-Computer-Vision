# Image Classification with Attention Mechanism 

# Overview
This repository contains code for building an image classification model with an attention mechanism using TensorFlow and Keras. The model is trained on a dataset consisting of approximately 4700 advertising images and 650 non-advertising images collected from various sources including web scraping, manual collection, and datasets from platforms like Kaggle and Hugging Face.

# Dataset
The dataset used for training the model is available in a zip file hosted on Google Drive. You can download the dataset from the following link: https://drive.google.com/file/d/1R7jkssicFNCQDUbnH9pRb9_n90L5ufNp/view?usp=sharing 

# Steps for Completion

Data Pre-processing:

Data collected from different sources is pre-processed to ensure consistency in size, format, and quality.
Images are resized to a uniform size and normalized.

Transfer Learning with VGG16:

* Utilize transfer learning with VGG16 for effective feature extraction.

* Load pre-trained VGG16 model without its top layers.

* Freeze base model layers to preserve pre-trained weights.
  
Evaluation Metrics and Visualization:

* Utilize confusion matrix, precision-recall curve, and ROC curve for evaluation.

* Use GRAD-CAM to visualize important image regions.
  
Feature Extraction and Attention Mechanism:

* Extract features from a specific layer of the pre-trained model.

* Implement attention mechanism to enhance model performance.

# THANK YOU 
