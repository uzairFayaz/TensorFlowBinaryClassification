# Binary Classification with TensorFlow

This repository contains a simple binary classification model implemented using TensorFlow and Keras. The model classifies data points based on two input features.

## Dataset
The dataset consists of randomly generated values, where the label is determined based on the sum of the two features:
- **Label = 1** if the sum of the two features is greater than 1.
- **Label = 0** otherwise.

## Model Architecture
The model is a simple feedforward neural network with the following layers:
- **Input Layer**: 2 neurons (for two features)
- **Hidden Layer 1**: 16 neurons, ReLU activation
- **Hidden Layer 2**: 8 neurons, ReLU activation
- **Output Layer**: 1 neuron, Sigmoid activation (for binary classification)

## Dependencies
To run this project, install the required dependencies:
```sh
pip install tensorflow numpy
```

## Running the Model
1. Clone the repository and navigate to the project directory.
2. Run the script:
   ```sh
   python binary_classification.py
   ```
3. The model will train and evaluate performance on the test set.

## Output
- The model trains for 20 epochs.
- Accuracy is displayed after training and evaluation.


---
Feel free to modify the model parameters and dataset generation logic to experiment with different configurations!
