# Supervised Learning

It supervise the learning process, meaning the data that you have collected here is labelled and so you know what input needs to be mapped to what output. 
This helps you correct your algorithm if it makes a mistake in giving you the answer.

Supervised Learning is the process of making an algorithm to learn to map an input to a particular output. This is achieved using the labelled datasets that you have collected. If the mapping is correct, the algorithm has successfully learned. 
Else, you make the necessary changes to the algorithm so that it can learn correctly. 
Supervised Learning algorithms can help make predictions for new unseen data that we obtain later in the future. 

---

<p align="center">
    <img src="Supervised_Learning.png" width="700" hight ="800">
</p>

---

## Why is it Important? 
- Learning gives the algorithm experience which can be used to output the predictions for new unseen data
- Experience also helps in optimizing the performance of the algorithm
- Real-world computations can also be taken care of by the Supervised Learning algorithms

## Types of Supervised Learning:
Supervised Learning has been broadly classified into 2 types.

- Regression
- Classification

### Regression:
Regression is the kind of Supervised Learning that learns from the Labelled Datasets and is then able to predict a continuous-valued output for the new data given to the algorithm. 
It is used whenever the output required is a number such as money or height etc. 

### Classification:
Classification, on the other hand, is the kind of learning where the algorithm needs to map the new data that is obtained to any one of the 2 classes that we have in our dataset. The classes need to be mapped to either 1 or 0 which in real-life translated to ‘Yes’ or ‘No’, ‘Rains’ or ‘Does Not Rain’ and so forth.
The output will be either one of the classes and not a number as it was in Regression.

## Advantages of Supervised Machine Learning

- You will have an exact idea about the classes in the training data.
- Supervised learning is a simple process for you to understand. In the case of unsupervised learning, we don’t easily understand what is happening inside the machine, how it is learning, etc.
- You can find out exactly how many classes are there before giving the data for training.
- It is possible for you to be very specific about the definition of the classes, that is, you can train the classifier in a way which has a perfect decision boundary to distinguish different classes accurately.
- After the entire training is completed, you don’t necessarily need to keep the training data in your memory. Instead, you can keep the decision boundary as a mathematical formula.
- Supervised learning can be very helpful in classification problems.
- Another typical task of supervised machine learning is to predict a numerical target value from some given data and labels.

## Disadvantages of Supervised Learning
Supervised Learning has a lot of challenges and disadvantages that you could face while working with these algorithms. 
These inlcudes: 
- You could overfit your algorithm easily
- Good examples need to be used to train the data
- Computation time is very large for Supervised Learning
- Unwanted data could reduce the accuracy
- Pre-Processing of data is always a challenge
- If the dataset is incorrect, you make your algorithm learn incorrectly which can bring losses

## References

1. https://medium.com/edureka/supervised-learning-5a72987484d0
2. https://pythonistaplanet.com/pros-and-cons-of-supervised-machine-learning/
