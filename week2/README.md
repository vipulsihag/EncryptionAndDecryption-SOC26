# Week2
The goal of this week was to create a MLP model to decrypt a caesar cipher (which was done manually in week1).

## Data Collection and Processing
The Data was made of two eBooks from Project Gutenberg. 
- The Great Gatsby by F. Scott Fitzgerald
- The Secret of Chimneys by Agatha Christie

The data was then processed to only have lower case English alphabets and common symbols like full stops, commas, hiphens etc.

Then the data was divided into chunks of 500 and each was encrypted using a caesar cipher with a random shift(This shift was stored in encryptionLabels.csv). Of each, 400 characters were used for training and 100 for testing. 

## The Model
Then a MLP model was trained on this data and tested. The hyperparameters are as follows:
- input size : 50 characters
- One embedding layer (each character to vector 16 dim vector)
- One hidden layer with size 128
- Output Size : 37
- Learning Rate : 0.01
- Loss : Cross Entropy Loss
- Optimiser : Adam Optimiser

## Result
Test Accuracy: 96.29% as compared to 2.7% for a random guess.