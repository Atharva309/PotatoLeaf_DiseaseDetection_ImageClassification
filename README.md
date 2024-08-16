# Potato Disease Image Classification using Transfer Learning

This project focuses on classifying potato leaves into three categories: early blight, healthy, and late blight. It utilizes transfer learning with the ResNet50V2 network, leveraging pre-trained weights for effective feature extraction.

## Dataset

- **Source**: [Plant Disease Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease?resource=download)
- **Content**: Images of potato leaves categorized into early blight, healthy, and late blight.

## Model

- **Architecture**: ResNet50V2 with transfer learning
- **Pre-trained Weights**: Frozen, with a new classification layer added
- **Compilation**: Adam optimizer, categorical cross-entropy loss
- **Accuracy**: 97.40% on the validation set

## Requirements

- TensorFlow 2.5.0
- Keras 2.5.0
- numpy 1.19.5
- matplotlib 3.2.2
- scikit-learn 0.24.2
- opencv-python 4.5.3.56

## How to Run

1. Clone the repository and set up the environment.
2. Download and preprocess the dataset.
3. Train the model using the provided script.
4. Evaluate the model’s performance on the validation set.

## Conclusion

The project demonstrates the effectiveness of transfer learning for high-accuracy classification of potato diseases, achieving a notable accuracy of 97.40% on the validation set.
