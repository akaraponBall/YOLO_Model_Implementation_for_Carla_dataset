# YOLO Model Implementation for Carla Object Detection dataset

## Objective
This project demonstrates how to implement object detection using a YOLO model in PyTorch. The pipeline includes:
- Processing images and labels into a YOLO-compatible dataset
- Building the YOLO model
- Building essential functions: loss function, IoU accuracy, and class accuracy
- Training the YOLO model on the prepared dataset

## Features
- **End-to-End Workflow**: From data preparation to model training.
- **PyTorch Implementation**: Uses EfficientNet as a feature extractor for transfer learning.

## Highlights
- **Feature Extractor:** Uses EfficientNet-B0 as the backbone for extracting high-level features.
- **Detection Head:** Custom dconvolutional layers that process the feature maps to output predictions
- **Loss Function:** Optimize Localization Loss, Confidence Loss, and classification loss.
- **Metrics:** Evaluate model predictions with IoU and per-class accuracy.

## Contributions
Feel free to contribute by submitting issues or pull requests.

## Acknowledgments
- [Inspired by the original YOLO paper](https://arxiv.org/abs/1506.02640)
- [Carla Object Detection Dataset from kaggle](https://www.kaggle.com/datasets/suraj520/carla-object-detection-dataset)

## Notes
- The YOLO model implemented in this project is not accurate enough for deployment due to limited computational resources for training and tuning. Building the most accurate YOLO model was not the primary objective of this project. However, contributions and improvements to enhance model performance are welcome.