
# What is  Machine Learning

Getting Computers (Machine) to learn without being explicitly Programmed.

> or

Getting Computers (Machine) to recognise patterns by examples, rather than programming it with specific rules. These patterns are found within Data

> or

_Building a model_ from example inputs to make data-driven predictions vs following  static program instructions

> or

“A computer program is said to learn from experience E concerning some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.” — Tom Michel.

Example-1:
Suppose your email program watches which emails you do or do not mark as spam, and based on that learns how to filter spam better. What is the task T in this setting?

1. Classify emails as spam or not spam.
2. Watching you label emails as spam or not spam.
3. The number (or fraction) of emails correctly classified as spam/not spam.
4. None of the above, this is not a machine learning algorithm.

* Label emails as spam or not spam (option-2) is the Experience (E)
* Classify emails as spam or not spam (option-1) is the Task (T)
* The number (or fraction) of emails correctly classified as spam/not spam (option-3) is the Performance (P)

Example-2: 
Playing checkers.

* E = the experience of playing many games of checkers
* T = the task of playing checkers.
* P = the probability that the program will win the next game.

# Categories of Machine Learning Algorithms

In general, any machine learning problem can be assigned to one of two broad classifications:

* Supervised learning
* Unsupervised learning
* Others: Reinforcement learning, Recommender Systems

![Image of ML Categories](/images/ml-categories.jpg)

## Supervised Learning

![Supervised ML](/images/supervised-ml.png)

We are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.

Supervised learning problems are categorised into 

* "regression" and
* "classification" problems

### Regression Problem

* We are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. 
* Continuous Data can take any value (within a range)
* Examples:
  * Given data about the size of houses on the real estate market, try to predict their price. Price as a function of size is a continuous output, so this is a regression problem.
  * Given a picture of a person, we have to predict their age by the given picture

### Classification Problem

* We are trying to predict results in a discrete output,  meaning that we are trying to map input variables into discrete categories.
* Discrete Data can only take specific values.
* Examples:
  * Given data about the size of houses on the real estate market, try to predict whether the house "sells for more or less than the asking price." Here we are classifying the houses based on price into two discrete categories.
  * Given a patient with a tumour, we have to predict whether a tumour is malignant or benign

### Applications of Supervised Machine Learning

1. Healthcare: Predicting patient diagnostics for doctors to review
2. Social Network: Predicting specific match preferences on a dating website for better compatibility
3. Finance: Predicting fraudulent activity on a credit card
4. E-commerce: Predicting customer churn
5. Biology: Finding patterns in gene mutations that could represent cancer
6. Real Estate: Predicting house prices for house buyers and house sellers

Machine Learning involves mapping from a set of inputs to set of outputs.

| Input (X)                | Output (Y)                    | Application          |
|--------------------------|-------------------------------|----------------------|
| Voice Recording          | Transcript                   | Speech Recognition   |
| Historical Market Data   | Future Market Data            | Trading Bots         |
| Photograph               | Caption                       | Image Tagging        |
| Drug Chemical Properties | Treatment Efficacy            | Pharma R&D           |
| Store Transaction Detail | Is the Transaction Fraudulent | Fraud Detection      |
| Recipe Ingredients      | Customer Reviews              | Food Recommendations |
| Purchase Histories       | Future Purchase behaviour     | Customer Retention   |
| Car Locations & Speed    | Traffic Flow                  | Traffic Lights       |
| Faces                    | Names                         | Face Recognition     |


## USupervised Learning

![UNSupervised ML](/images/unsupervised-ml.png)

With supervised machine learning, you have an input variable that consists of _labeled training data_ and a _desired output variable_. An algorithm to analyse the training data is used to model the function that maps the input to the output. This modelled function maps new, unknown examples by generalising from the training data to anticipate results in unseen situations.

With unsupervised machine learning, you have unlabeled data, and the outcomes to problems are mostly unknown. The system learns by itself by discovering the natural patterns within the given data, (such as a clustering structure, a low-dimensional manifold, or a sparse tree and graph). Technically, there are bound to be wrong answers, since there is a certain degree of probability. However, just like how we humans work, the strength of machine learning lies in its ability to recognise mistakes, learn from them, and to eventually make better estimations next time around.

### Adapted From

* [Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning/lecture/Ujm7v/what-is-machine-learning)
* [A Beginner's Guide to Machine Learning](https://www.linkedin.com/pulse/beginners-guide-machine-learning-randy-lao-/?trk=v-feed "Permalink to ")
* [Machine Learning vs Deep Learning](https://mc.ai/machine-learning-vs-deep-learning/)
* [Google Machine Learning](https://www.youtube.com/watch?v=cKxRvEZd3Mw&list=PLT6elRN3Aer7ncFlaCz8Zz-4B5cnsrOMt)
* [Machine Learning Explained](http://bigdata-madesimple.com/machine-learning-explained-understanding-supervised-unsupervised-and-reinforcement-learning/)

### Tools

[Markdown Table Tool](https://www.tablesgenerator.com/markdown_tables)