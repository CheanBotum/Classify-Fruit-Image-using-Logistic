# Fruit Image Classification with Logistic Regression

## Overview
This project focuses on building a fruit image classification model using logistic regression. The dataset contains a total of 13,897 images, distributed across 81 different fruit classes. The goal is to classify fruit images accurately into their respective classes.

## Dataset
The dataset consists of fruit images organized into 81 different classes. Each class represents a type of fruit. The dataset has the following characteristics:
- Number of Images: 13,897
- Number of Classes: 81
- Image Dimensions: 64x64 pixels (RGB)

## Model
The classification model used for this project is logistic regression. It's a simple yet effective model for multi-class classification tasks. The logistic regression model takes flattened image inputs and predicts the class probabilities for each fruit category.

## Usage
1. **Data Preparation**: Make sure to organize your fruit images into 81 different folders, each representing a specific fruit class. Ensure that the images are resized to 64x64 pixels.

2. **Training**: Train the logistic regression model using the provided code. You may need to adjust hyperparameters such as batch size and learning rate based on your dataset.

3. **Evaluation**: Evaluate the model's performance using various metrics, such as accuracy, precision. Ensure you have a validation set for this purpose.

4. **Testing**: Test the trained model on a separate test dataset to assess its real-world performance.

5. **Inference**: Use the model to make predictions on new fruit images.

## Requirements
- Python 3.x
- PyTorch (for model training)
- Jupyter Notebook (for running the provided code)
- Matplotlib (for visualizing images and results)

## Files
- `train.ipynb`: Jupyter Notebook containing the code for training the logistic regression model.
- `test.ipynb`: Jupyter Notebook for testing the trained model.
- `data/`: Folder containing the fruit image dataset.
- `model/`: Folder for saving trained models.
- `utils/`: Utility functions for data preprocessing and evaluation.

## Results
It is good with 99.41% true.
## Acknowledgments
 tutorials used for this project https://realpython.com/logistic-regression-python/


