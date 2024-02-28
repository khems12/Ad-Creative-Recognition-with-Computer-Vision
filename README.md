#Image Classification with Attention Mechanism
Overview
This repository contains code for building an image classification model with an attention mechanism using TensorFlow and Keras. The model is trained on a dataset consisting of approximately 4700 advertising images and 650 non-advertising images collected from various sources including web scraping, manual collection, and datasets from platforms like Kaggle and Hugging Face.

Dataset
The dataset used for training the model is available in a zip file hosted on Google Drive. You can download the dataset from the following link: Dataset Zip File

Steps for Completion
Data Pre-processing:

Data collected from different sources is pre-processed to ensure consistency in size, format, and quality.
Images are resized to a uniform size and normalized.
Choosing VGG16 Pre-trained Model:

The VGG16 pre-trained model is chosen for its effectiveness in feature extraction from images.
Loading Pre-trained VGG16 Model without Top Layers:

The pre-trained VGG16 model is loaded without its top layers to retain only the convolutional base.
Freezing Base Model Layers:

The layers of the base model are frozen to prevent them from being updated during training, thus preserving the pre-trained weights.
Model Evaluation:

The trained model achieves an accuracy of around 97% and an F1 score of 0.97 on the validation dataset.
Evaluation Metrics:

Confusion matrix, precision-recall curve, and receiver operating characteristic (ROC) curve are used to evaluate the performance of the model.
Visualization Techniques:

GRAD-CAM is utilized to visualize heatmaps highlighting important regions of the image for classification.
Feature Extraction:

Features are extracted from a specific layer of the pre-trained VGG16 model to understand the representations learned by the model.
Attention Mechanism:

Attention mechanism is implemented to enhance the model's performance by focusing on important regions of the image during classification.
Usage
Download the dataset zip file from the provided Google Drive link.
Extract the dataset and ensure proper organization of image files.
Follow the instructions in the code to pre-process the data, train the model, and evaluate its performance.
Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The project draws inspiration from the concept of attention mechanisms in neural networks.
Special thanks to the contributors and maintainers of TensorFlow and Keras for their valuable libraries.
