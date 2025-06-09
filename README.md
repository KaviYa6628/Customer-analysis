 # customer analysis

This project focuses on analyzing customer data to predict customer loyalty using a deep learning model based on an Artificial Neural Network (ANN). It helps determine whether customers are likely to stay with the business or churn (exit), allowing businesses to take proactive steps in customer retention.

# project objective
1.Predict customer loyalty using historical and behavioral data.
2.Classify customers as loyal (staying) or churn (exiting).
3.Use deep learning techniques for accurate prediction.

# Prerequisites
Python 3.7+
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow / keras

# Overview

The goal is to use customer data to predict their loyalty status.The core model is an Artificial Neural Network (ANN) trained on features like customer history, transactions, and behavior.
It outputs whether a customer is likely to stay with the company or churn (exit).
# set up
  Clone this repository or download the code.
  Install the required dependencies: pip install tensorflow keras scikit-learn matplotlib seaborn numpy
Make sure you have access to the dataset. This code assumes you have the dataset  placed in a folder, accessible via path.


## Model Architecture
This project uses a deep learning-based Artificial Neural Network (ANN) to classify customer loyalty based on historical data. The model is trained to understand patterns that indicate whether a customer is likely to remain loyal or leave the service.
Type: Feedforward Neural Network
Layers: Input layer → Hidden Layers (2-3) → Output layer
Hidden Layers: ReLU
Output Layer: Softmax or Sigmoid (for binary classification)
Loss Function: Binary Crossentropy
Optimizer: Adam
Evaluation Metric: Accuracy, Precision, Recall

# Acknowledgement
This project was inspired by the importance of understanding customer behavior and loyalty trends to improve business strategies and customer retention. The work was supported by open-source tools and datasets, and driven by the goal of building accurate and scalable predictive models.

# output details
The model is tested using a batch of customer data — not just one customer at a time. Each input is a row from the test dataset, and includes multiple customer features like age, tenure, purchase behavior, etc.
The output of the model is evaluated using a confusion matrix:

[[144   8]
 [ 39   9]]

144 → Loyal customers correctly predicted as loyal

8 → Loyal customers wrongly predicted as disloyal

39 → Disloyal customers wrongly predicted as loyal

9 → Disloyal customers correctly predicted as disloyal

The model takes many customers' data at once, and for each customer, it looks at their multiple features to make a prediction











