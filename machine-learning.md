# What is Machine Learning
Getting Computers (Machine) to learn without being explicitly Programmed.

> or

Getting Computers (Machine) to recognize patterns by examples, rather than programming it with specific rules. These patterns are found within Data

> or

“A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.” — Tom Michel

> or

_Building a model_ from example inputs to make data-driven predictions vs. following  static program instructions


Example-1:
Suppose your email program watches which emails you do or do not mark as spam, and based on that learns how to better filter spam. What is the task T in this setting?

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
* Others : Reinforcement learning, Recommender Systems


## Supervised Learning
We are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.

Supervised learning problems are categorized into 
* "regression" and 
* "classification" problems. 

### Regression Problem : 
* We are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. 
* Continuous Data can take any value (within a range)
* Examples:
  * Given data about the size of houses on the real estate market, try to predict their price. Price as a function of size is a continuous output, so this is a regression problem.
  * Given a picture of a person, we have to predict their age on the basis of the given picture


### Classification Problem:  
* We are  trying to predict results in a discrete output,  meaning that we are trying to map input variables into discrete categories.
* Discrete Data can only take certain values.
* Examples:
  * Given data about the size of houses on the real estate market, try to predict whether the house "sells for more or less than the asking price." Here we are classifying the houses based on price into two discrete categories.
  * Given a patient with a tumor, we have to predict whether the tumor is malignant or benign





1. [Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning/lecture/Ujm7v/what-is-machine-learning)
2. [A Beginner's Guide to Machine Learning](https://www.linkedin.com/pulse/beginners-guide-machine-learning-randy-lao-/?trk=v-feed "Permalink to ")
3. [Machine Learning vs. Deep Learning](https://mc.ai/machine-learning-vs-deep-learning/)
4. [Google Machine Learning](https://www.youtube.com/watch?v=cKxRvEZd3Mw&list=PLT6elRN3Aer7ncFlaCz8Zz-4B5cnsrOMt)
