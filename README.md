# Potato Disease Image Classification using Transfer Learning

This is a deep learning project that aims to classify three types of potato diseases: early blight, healthy, and late blight. The model uses transfer learning with a pre-trained ResNet50V2 network and was trained on the [Plant Disease dataset](https://www.kaggle.com/datasets/emmarex/plantdisease?resource=download) from Kaggle.

## Dataset

The dataset consists of 3 folders containing images of early blight, healthy, and late blight potato leaves.

## Model

The model uses transfer learning with a pre-trained ResNet50V2 network. The pre-trained weights are frozen, and a new classification layer is added to the top of the network. The model is compiled with the Adam optimizer and categorical cross-entropy loss function. The model achieved an accuracy of 97.40% on the validation set.
-TensorFlow 2.5.0
-Keras 2.5.0
-numpy 1.19.5
-matplotlib 3.2.2
-scikit-learn 0.24.2
-opencv-python 4.5.3.56

