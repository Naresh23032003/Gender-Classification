# Gender Classification

This project focuses on gender classification using Convolutional Neural Networks (CNNs) to predict whether an image corresponds to a male or a female.

## Description

The dataset used for this project is the Male Female image dataset obtained from Kaggle. The model architecture consists of multiple convolutional layers followed by fully connected layers. The project leverages GPU acceleration for faster model training and evaluation.

## Usage

1. Install the required libraries by executing the provided setup instructions.
2. Ensure that GPU acceleration is available for faster training and evaluation.
3. Download the dataset from the provided link or use the Kaggle API to fetch it.
4. Train the model using the provided notebook. The model will automatically utilize the available GPU if configured correctly.
5. Evaluate the model's performance using the test dataset.
6. Save the trained model for future use.

## Setup Instructions

1. Install Jovian: `!pip install jovian --upgrade -q`.
2. Ensure that GPU acceleration is enabled in the notebook settings (Runtime > Change runtime type > Hardware accelerator: GPU).
3. Upload the dataset to the notebook environment or use the Kaggle API.
4. Follow the code cells in the notebook to train and evaluate the model.
5. Save the trained model for future inference.

## Conclusion

The trained model achieved an accuracy of 96.1% on the test dataset. Utilizing GPU acceleration significantly reduced the training and evaluation time, making the process more efficient. Future improvements could involve experimenting with different model architectures, hyperparameters, and datasets.

## Acknowledgements

- The dataset was obtained from Kaggle.
- The project was developed using Google Colab with GPU acceleration.
- Dependencies: PyTorch, Matplotlib, Pandas, NumPy, and Jovian.

