# cleaned-vs-dirty-plates

## Overview
A dataset of labeled images of cleaned and dirty plates used for binary image classification. This project demonstrates training a classifier to distinguish between clean and dirty plates.

## Dataset
- Contains images labeled as **cleaned** and **dirty**.
- Dataset available on Kaggle: [https://www.kaggle.com/code/sagar1subedi/cleaned-vs-dirty-v2]

## Usage
- Load and preprocess the images using torchvision transforms.
- Train a classification model such as ResNet18 on the labeled dataset.
- Run inference on test images and generate predictions.
- Example code snippets can be found in the repository.

## Submission
- Prepare a submission file (CSV) with columns `id` and `label`.
- `id` corresponds to the image file number (without extension).
- `label` is the predicted class ('cleaned' or 'dirty').

## Results
- Model accuracy and other metrics can be added here.
- Sample predictions visualization is available.

## Requirements
- Python 3.x
- PyTorch
- torchvision
- PIL (Pillow)
- matplotlib (optional, for visualization)

## How to contribute
Feel free to open issues or submit pull requests to improve this project.
