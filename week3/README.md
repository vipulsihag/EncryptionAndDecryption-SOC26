# Week3
This week involved creating a recurrent neural network for sentiment analysis.
## Model
A simple Recurrent Neural Network (RNN) is used for 3-class sentiment classification(Positive, Negative, Neutral).
- Embedding layer: Converts each input token into a 64 dim vector.
- RNN layer: Processes the sequence using a single-layer RNN with 128 hidden units. 
- Fully Connected layer: Maps the 128-dimensional feature vector to 3 output logits, corresponding to the sentiment classes.

The Hyperparameters are as follows:
- Embedding dimension: 64
- Hidden layer size: 128
- Batch size: 32
- Learning rate: 0.0005
- Optimizer: Adam
- Loss function: CrossEntropyLoss
- Number of epochs: 5
- Output classes: 3