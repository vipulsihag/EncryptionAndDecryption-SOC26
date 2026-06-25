# Week1
This week invloved the basics of ciphers and neural networks.
## Q1
It involved building a basic neural network to predict the species (among 3 options) of a plant using 4 parameters of petal, sepal width and height. 
The Hyper Parameters are as follows: 
- input_size = 4
- output_size = 3
- neurons = 16
- learning_rate = 0.01

This had a test accuracy of 96.67% as compared to 33% for a random guess.

## Q2
Given encrypted text and the knowledge that it was a caesar cipher, the task was to decode it(obviously).
I had two approaches for this : 
- Use brute force and print a 'decryption' using all possible shifts and identify the only readable one among them. 
- Use frequency analysis to identify which characters represent common letters like e and t, and full stops. And based on this information, predict the shift the caesar cipher is using.

