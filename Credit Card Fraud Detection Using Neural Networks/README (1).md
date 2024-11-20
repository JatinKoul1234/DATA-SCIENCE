
# CREDIT CARD FRAUD DETECTION USING NEURAL NETWORKS 

## 1. Project Description

This project uses artificial neural networks (ANN) to identify fraudulent credit card transactions, tackling the pressing challenge of fraud detection in environments with high transaction volumes. By examining a rich dataset, the model distinguishes between legitimate and fraudulent transactions, utilizing historical trends and user behaviour to improve accuracy. The goal is to provide real-time fraud detection, reduce financial losses, and enhance customer confidence in online transactions. With its ability to learn from new data (Backpropogation), the model aims to continuously refine its performance, ultimately contributing to a more secure digital payment landscape.


## Requirements Include

1.TensorFlow 

2.Keras

3.Pandas 

4.NumPy 

5.Seaborn 

6.Plotly 

7.Matplotlib
## Dataset

The model is trained on a dataset containing details of credit card transactions, such as the amount, location,jobs etc. The dataset has been sourced form Kaggle.

Link for the dataset:https://www.kaggle.com/datasets/kartik2112/fraud-detection?select=fraudTrain.csv
## Model Architecture

The core of this project is a neural network architecture designed for binary classification:

I.Input Layer: Accepts transaction features (e.g., amount, location). 

II.Hidden Layers: Several dense layers with ReLU activations to capture non-linear patterns. 

III.Output Layer: A sigmoid function outputs probabilities for the binary classification (fraud or not).
## Training Process

The model is trained using:

I.Loss Function: Binary Cross-Entropy for binary classification. 

II.Optimizer: Adam optimizer to adjust learning rates. 

III.Batch Size and Epochs: Defined based on experimentation to balance accuracy and training efficiency.

The model iteratively adjusts weights through backpropagation to improve its predictive accuracy, learning from both fraudulent and legitimate transaction examples.
## Evaluation and Results

The model is evaluated using:

I.Accuracy: Overall classification accuracy.

II.Precision: Fraction of identified fraudulent transactions that are actually fraud.

III.Recall: Ability to capture all true fraudulent transactions. 

IV.F1 Score: Balances precision and recall for a comprehensive evaluation