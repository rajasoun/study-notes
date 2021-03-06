
# What is  Machine Learning

Getting Machine to learn without being explicitly Programmed.

> or
 
“A computer program is said to learn  
   from experience E    
   with respect to some class of tasks T   
   and performance measure P,               
if its performance at tasks in T, as measured by P, improves with experience E.”   
 — Tom Michel.



We, humans, learn mostly from our past experiences.  
Let us take an example, remember the first time we started using smartphones. 
During the first time experience, we might have performed the class of tasks like switching on/ off the phone, browse the Internet, listen to music, ordering food etc. 
We consider ourselves learnt the skills of using a smartphone if we do the same task faster next time.

A human is said to learn 
   from experience of smartphone usage   
   with respect to class of tasks like switching on/ off the phone, browse the Internet, listen to music, ordering food etc. 
   and performance measure  faster,               
if our performance at tasks improves with experience measured by fastness 

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

With supervised machine learning, you have an input variable that consists of _labeled training data_ and a _desired output variable_. An algorithm to analyse the training data is used to model the function that maps the input to the output. This modelled function maps new, unknown examples by generalising from the training data to anticipate results in unseen situations.

In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.

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

## UnSupervised Learning

With unsupervised machine learning, you have unlabeled data, and the outcomes to problems are mostly unknown. The system learns by itself by discovering the natural patterns within the given data, (such as a clustering structure, a low-dimensional manifold, or a sparse tree and graph). Technically, there are bound to be wrong answers, since there is a certain degree of probability. However, just like how we humans work, the strength of machine learning lies in its ability to recognise mistakes, learn from them, and to eventually make better estimations next time around.

Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.

We can derive this structure by clustering the data based on relationships among the variables in the data.
With unsupervised learning there is no feedback based on the prediction results.

Examples:

Clustering: Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.

Non-clustering: The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a cocktail party).

![UnSupervised ML](/images/unsupervised-ml.png)

## Which Machine Learning Algorithm Should I Use?

![ML Cheat Sheet](/images/machine-learning-cheet-sheet.png)

## Terms
* Linearity - Property of a mathematical function that can be graphically represented as a straight line  
* Linear Regression -  Linear approach to modelling the relationship between a dependent variable and one or more independent variables  
* Input Variable/Independent Variable : An independent variable is a variable that is manipulated to determine the value of a dependent variable   
* Output Variable/Dependent Variable : An dependent variable is a variable that represents the output or outcome 
Hypothesis  
* Cost Function or Mean Square Error :  Measures the average squared difference between the desired  output  and actual output is estimated  
* Linear Programming : Mathematical technique for maximizing or minimizing a linear function of several variables, such as output or cost  

### Adapted From

* [Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning/lecture/Ujm7v/what-is-machine-learning)
* [A Beginner's Guide to Machine Learning](https://www.linkedin.com/pulse/beginners-guide-machine-learning-randy-lao-/?trk=v-feed "Permalink to ")
* [Machine Learning vs Deep Learning](https://mc.ai/machine-learning-vs-deep-learning/)
* [Google Machine Learning](https://www.youtube.com/watch?v=cKxRvEZd3Mw&list=PLT6elRN3Aer7ncFlaCz8Zz-4B5cnsrOMt)
* [Machine Learning Explained](http://bigdata-madesimple.com/machine-learning-explained-understanding-supervised-unsupervised-and-reinforcement-learning/)
* [ML Cheat Sheet](https://www.kdnuggets.com/2017/06/which-machine-learning-algorithm.html)

### Datasets

* [UC Irvine Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php)
* [Linear Regression Dataset](http://people.sc.fsu.edu/~jburkardt/datasets/regression/regression.html)
* [24 Ultimate Data Science Projects To Boost Your Knowledge and Skills](https://www.analyticsvidhya.com/blog/2018/05/24-ultimate-data-science-projects-to-boost-your-knowledge-and-skills/)

### Tools

[Markdown Table Tool](https://www.tablesgenerator.com/markdown_tables)

### Further Readings
* [Bringing the benefits of AI to everyone By Google](https://ai.google/about/)
* [ML Courses From Coursera](https://www.coursera.org/courses?languages=en&query=machine+learning&userQuery=machine+learning)
* [Structuring Machine Learning Projects](https://www.coursera.org/learn/machine-learning-projects#)
* [Calculus](https://betterexplained.com/articles/a-gentle-introduction-to-learning-calculus/)

