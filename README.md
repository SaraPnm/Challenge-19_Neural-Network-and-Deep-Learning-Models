## Project Overview
We’ll explore and implement neural networks using the TensorFlow platform in Python. We’ll build our own machine learning model that will be able to predict the success of a venture paid by Alphabet soup.

The goals of this challenge are to:

1. Import, analyze, clean, and preprocess a “real-world” classification dataset.
2. Select, design, and train a binary classification model of your choosing.
3. Optimize model training and input data to achieve desired model performance.


## Resources
- Python 3.7

# Discussion of results
1. How many neurons and layers did you select for your neural network model? Why?
I used 2 layers with 10 and 7 neurons. This was the efficient model to result in the requested accuracy.


2. Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
Yes. I took following steps to enhance the model performance:
  - tried different number of layers and neurons in each layer. 
  - changed the number of categories as well as bining method in CLASSIFICATION and APPLICATION_TYPE variables
  - tested different activation functions

3. If you were to implement a different model to solve this classification problem, which would you choose? Why?
I could use both Random Forest and Logistic Regression, but since the accuracy is more important compared to interpretability in this specific problem, I prefer Random Forest.
