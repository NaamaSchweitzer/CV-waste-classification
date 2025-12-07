# CV-waste-classification

This repository contains the necessary resources and notebooks for developing an object detection model focused on classifying specific types of waste and debris.

## 🎯 Project Aim

The main objective of this project is to develop and assess a robust object detection model for trash detection. This involves training a computer vision model to automatically identify and locate different categories of debris in images.

## 📊 Dataset Overview

The model is trained using the **alyyan/trash-detection** dataset, sourced from Kaggle. This dataset provides images and labels necessary for training an object detection model to classify environmental debris.

## 🗑️ Detected Classes

The model is designed to detect instances belonging to the following four distinct classes:

1. **dirt**
2. **liquid**
3. **marks**
4. **trash**

## 💻 Setup and Environmental Variables

To successfully download and process the dataset from Kaggle within the Colab environment (as demonstrated in the notebook), you must authenticate using your Kaggle API token.

Please ensure the following environment variables or Colab secrets are set:

- **KAGGLE_USERNAME**: Your Kaggle account username.
- **KAGGLE_KEY**: Your Kaggle API key (found in the `kaggle.json` file).

## 📝 Notebook

The entire pipeline, including data download, preprocessing, and model training, is contained in the main notebook:

- `CV_Waste_Classification.ipynb`
- `ModelProcessing.ipynb`
