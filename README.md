📉 Customer Churn Prediction using Neural Network
This project predicts customer churn using a simple feedforward neural network built with one input layer, one hidden layer, and one output layer. The model was trained on customer data to classify whether a customer will churn (1) or stay (0).

🧠 Model Overview
Architecture:

Input Layer

1 Hidden Layer with ReLU activation

Output Layer with Sigmoid activation

Loss Function: Binary Cross Entropy

Optimizer: Adam

Activation Functions:

ReLU for input and hidden layers

Sigmoid for output layer

📊 Performance
Metric	Value
Train Accuracy	81%
Test Accuracy	79%

🧾 Classification Report on Test Data
Class	Precision	Recall	F1-Score	Support
0 (No Churn)	0.83	0.89	0.86	999
1 (Churn)	0.67	0.56	0.61	408

Overall Accuracy: 79%

Macro Average: Precision: 0.75, Recall: 0.72, F1-score: 0.73

Weighted Average: Precision: 0.78, Recall: 0.79, F1-score: 0.79

🛠 Technologies Used
Python

Pandas, NumPy

Scikit-learn

TensorFlow / Keras (or PyTorch if used — update accordingly)

Matplotlib / Seaborn (for visualizations)
