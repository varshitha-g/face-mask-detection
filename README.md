# Face Mask Detection

This repository contains a machine learning project aimed at detecting whether individuals are wearing face masks. Using Convolutional Neural Networks (CNN), the project classifies images into two categories: With Mask and Without Mask. This solution can be applied in real-time applications to ensure mask compliance in public areas.

## Project Overview

The Face Mask Detection project leverages deep learning techniques to build an image classification model capable of identifying face masks in images. The model can be used to enhance public safety by automatically monitoring mask-wearing in surveillance systems or other applications.

## Dataset

The dataset for this project consists of images labeled with "With Mask" and "Without Mask." It includes a diverse set of images collected from various sources to improve model accuracy across different demographics and environments. The dataset can be found in the data/ folder.

## Repository Structure

data/: Contains training and test datasets.

notebooks/: Jupyter notebooks for data exploration, model training, and evaluation.

models/: Saved model files for future deployment.

scripts/: Python scripts for data preprocessing, model training, and prediction.

output/: Sample outputs, visualizations, and evaluation metrics.

## Installation

To set up this project, ensure you have Python 3 and install the necessary libraries:

tensorflow or keras

opencv-python

numpy

matplotlib

## Usage

Clone the repository:
                  git clone https://github.com/varshitha-g/face-mask-detection.git
Explore the Jupyter notebooks in the notebooks/ folder for data preprocessing, model training, and evaluation.

Run the detection script on new images or video feeds to classify individuals as With Mask or Without Mask.
## Model Architecture

This project uses a Convolutional Neural Network (CNN) for image classification. Key steps include:

Data Augmentation: Enhancing the dataset with transformations to improve model robustness.

Model Training: Training the CNN model on labeled data to achieve accurate mask detection.

Evaluation: Evaluating model performance using metrics like accuracy, precision, recall, and F1 score.

## Results & Insights

The trained model demonstrates:

High accuracy in distinguishing between individuals With Mask and Without Mask.

Effective generalization across different lighting conditions and facial orientations.

## Applications

This face mask detection model can be deployed in various applications:

Real-time mask detection in CCTV systems.
Mask compliance monitoring in public spaces like malls, airports, and offices.
