# Breast Cancer Classification

This repository contains the code and resources for the Breast Cancer Classification project. The goal of this project is to accurately classify breast cancer histology images using an ensemble of three different deep learning architectures. The model is trained on the BACH: Breast Cancer Histology images dataset and achieves an accuracy of 90%, which is 3% higher than the competition.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)

## Introduction

Breast cancer is one of the most common cancers affecting women worldwide. Early and accurate detection is crucial for effective treatment and improved survival rates. This project leverages the power of deep learning to classify breast cancer histology images with high accuracy.

## Dataset

The model is trained on the [BACH: Breast Cancer Histology images dataset](https://www.kaggle.com/datasets/truthisneverlinear/bach-breast-cancer-histology-images). This dataset contains histology images that are categorized into four classes: normal, benign, in situ carcinoma, and invasive carcinoma.

## Model Architecture

The model ensemble consists of three different architectures:

1. **EfficientNetV2M**
2. **ConvNeXtTiny**
3. **EfficientNetB3**

The final prediction is determined by the majority vote from these three models.

## Training

The training process involves the following steps:

1. Preprocess the dataset images to the required input size for each model.
2. Train each model individually on the training set.
3. Evaluate each model on the validation set.
4. Combine the predictions of the three models using a majority vote to get the final prediction.

## Results

The ensemble model achieves an accuracy of 90% on the validation set, which is 3% higher than the competition.
