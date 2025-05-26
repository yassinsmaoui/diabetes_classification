# Classification of Diabetes

This project implements a custom Multi-Layer Perceptron (MLP) from scratch in Python to perform binary classification on the Pima Indians Diabetes dataset.

##  Objective

The goal is to build and train a neural network without using any deep learning frameworks (e.g., TensorFlow, PyTorch), and evaluate its performance on diabetes prediction.

##  Files

- `Classification_of_Diabetes.ipynb`: Jupyter notebook with full code and explanations.
- `diabetes.csv`: Dataset used for training and testing.
- `roc_curve.png`, `adam_curves.png`, etc.: Visualizations of training results.
- `README.md`: Project overview and instructions.

##  Features

- Manual implementation of:
  - Forward and backward propagation
  - Activation functions (ReLU, Sigmoid)
  - Gradient descent and Adam optimization
  - L2 regularization and dropout
  - ROC and AUC analysis
- Support for training/validation/test splitting
- Performance metrics: Accuracy, F1-score, AUC

##  Results

| Metric     | Score  |
|------------|--------|
| Accuracy   | 76%    |
| F1-Score   | 0.77   |
| AUC-ROC    | 0.79   |

##  How to Run

```bash
pip install -r requirements.txt  # if available
jupyter notebook
# Then open 'Classification_of_Diabetes.ipynb'
