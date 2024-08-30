
# Zero-Shot Classification via Attribute-Driven Prototype Estimation

## Overview

This project aims to implement zero-shot classification by leveraging attribute-driven prototype estimation. It enables classification of samples from unseen classes by creating prototypes based on known classes, thus avoiding the need for model retraining.

## Project Components

- **Prototype Creation**: Prototypes are developed using attribute data from the dataset, serving as reference points in the feature space for zero-shot classification.

- **Classification Method**: The classification is performed by calculating distances between samples and the established prototypes. The sample is assigned to the class of the nearest prototype.

## Dataset

You can download the dataset used for this project from the following link:
[Download Dataset](https://tinyurl.com/cs771-a23-hw1dat)

## Requirements

- Python 3.x
- NumPy
- scikit-learn
- pandas
- matplotlib


