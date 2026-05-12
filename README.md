# part-1-neural-network-analysis

# Part 1 - Neural Network Fundamentals and Training Behavior Analysis

## Project Overview

The objective of this project is to build a feed-forward neural network model for customer churn prediction. 
The project focuses on understanding how neural networks learn through forward propagation, loss calculation, backpropagation, and parameter updates.

The dataset contains customer-related information such as subscription details, usage behavior, customer service interactions, and payment information. 
The target variable is `churn`, where:
- 0 = Customer retained
- 1 = Customer churned

---

## Dataset Information

Dataset used:
- `customer_churn_nn.csv`

Additional reference file:
- `data_dictionary.md`

The dataset includes:
- Numerical features
- Categorical features
- Binary target variable

Categorical columns were encoded before training the neural network model.

---

## Project Workflow

The following steps were performed in this project:

1. Dataset loading and exploration
2. Missing value analysis
3. Target variable distribution analysis
4. Data preprocessing
5. Encoding categorical variables
6. Feature scaling
7. Train-test split
8. Neural network model creation
9. Model training and evaluation
10. Hyperparameter experimentation
11. Final reflection and analysis

---

## Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## Neural Network Architecture

The feed-forward neural network contains:
- Input layer
- Hidden layers with ReLU activation
- Output layer with sigmoid activation

The model was compiled using:
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy

---

## Model Evaluation

The model was evaluated using:
- Test accuracy
- Test loss
- Confusion matrix
- Classification report
- Accuracy and loss curves

The model demonstrated stable learning behavior and was able to identify customer churn patterns with reasonable accuracy.

---

## Hyperparameter Experimentation

Multiple experiments were performed by changing:
- Number of neurons
- Batch size
- Number of epochs

The results were compared using a model comparison table to analyze how hyperparameters affected model performance.

---

## Key Learnings

This project helped in understanding:
- Neural network fundamentals
- Importance of activation functions
- Role of weights and biases
- Impact of learning rate
- Underfitting and overfitting behavior
- Model evaluation techniques

---

## Repository Structure

```text
part-1-neural-network-analysis/
│
├── dataset/
├── results/
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

## Dataset Source

Dataset provided as part of the assignment dataset package.

