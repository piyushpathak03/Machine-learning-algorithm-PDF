# Machine Learning and All Algorithms
* [Machine Learning](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/machine%20learning.jpeg)

“Machine Learning is the science of getting computers to learn and act like humans do, and improve their learning over time in autonomous fashion, by feeding them data and information in the form of observations and real-world interactions.”

### Supervised machine learning            
Supervised machine learning trains itself on a labeled data set. That is, the data is labeled with information that the machine learning model is being built to determine and that may even be classified in ways the model is supposed to classify data. For example, a computer vision model designed to identify purebred German Shepherd dogs might be trained on a data set of various labeled dog images.  

### Unsupervised machine learning
Unsupervised machine learning ingests unlabeled data—lots and lots of it—and uses algorithms to extract meaningful features needed to label, sort, and classify the data in real-time, without human intervention. Unsupervised learning is less about automating decisions and predictions, and more about identifying patterns and relationships in data that humans would miss. Take spam detection, for example—people generate more email than a team of data scientists could ever hope to label or classify in their lifetimes. An unsupervised learning algorithm can analyze huge volumes of emails and uncover the features and patterns that indicate spam (and keep getting better at flagging spam over time).

### Semi-supervised learning 
Semi-supervised learning offers a happy medium between supervised and unsupervised learning. During training, it uses a smaller labeled data set to guide classification and feature extraction from a larger, unlabeled data set. Semi-supervised learning can solve the problem of having not enough labeled data (or not being able to afford to label enough data) to train a supervised learning algorithm. 

### Reinforcement machine learning
Reinforcement machine learning is a behavioral machine learning model that is similar to supervised learning, but the algorithm isn’t trained using sample data. This model learns as it goes by using trial and error. A sequence of successful outcomes will be reinforced to develop the best recommendation or policy for a given problem.


* [Statistics](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/00%20Statistics)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/statistics.jpg)

Statistics is a field of mathematics that is universally agreed to be a prerequisite for a deeper understanding of machine learning. Although statistics is a large field with many esoteric theories and findings, the nuts and bolts tools and notations taken from the field are required for machine learning practitioners.


* [Bias-Variance](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Bias_Variance)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/bias-variance.png)

If the algorithm is too simple (hypothesis with linear eq.) then it may be on high bias and low variance condition and thus is error-prone. If algorithms fit too complex ( hypothesis with high degree eq.) then it may be on high variance and low bias. In the latter condition, the new entries will not perform well. Well, there is something between both of these conditions, known as Trade-off or Bias Variance Trade-off.


* [Cross-Validation](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Cross%20Validation)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/Cross-Validation.jpg)

Cross validation is a model evaluation method that is better than residuals. The problem with residual evaluations is that they do not give an indication of how well the learner will do when it is asked to make new predictions for data it has not already seen. One way to overcome this problem is to not use the entire data set when training a learner. Some of the data is removed before training begins. Then when training is done, the data that was removed can be used to test the performance of the learned model on new data. This is the basic idea for a whole class of model evaluation methods called cross validation.


* [Gradient Descent](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Gradient%20Descent)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/gradient%20descent.jpg)

Gradient descent is a first-order iterative optimization algorithm for finding a local minimum of a differentiable function. The idea is to take repeated steps in the opposite direction of the gradient (or approximate gradient) of the function at the current point, because this is the direction of steepest descent.


* [Metrics in machine learning](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Metrics)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/Metrics.png)

Evaluation metrics are tied to machine learning tasks. There are different metrics for the tasks of classification, regression, ranking, clustering, topic modeling, etc. Some metrics, such as precision-recall, are useful for multiple tasks. Classification, regression, and ranking are examples of supervised learning, which constitutes a majority of machine learning applications.


# Machine Learning Algorithms

* [Linear Regression](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Linear%20Model)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/Linear%20models.png)

Simple linear regression is useful for finding relationship between two continuous variables. One is predictor or independent variable and other is response or dependent variable. It looks for statistical relationship but not deterministic relationship. Relationship between two variables is said to be deterministic if one variable can be accurately expressed by the other. For example, using temperature in degree Celsius it is possible to accurately predict Fahrenheit. Statistical relationship is not accurate in determining relationship between two variables. For example, relationship between height and weight.


* [Logistics Regression](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Logistic)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/Logistics%20regression.png)

Logistic regression is named for the function used at the core of the method, the logistic function.The logistic function, also called the sigmoid function was developed by statisticians to describe properties of population growth in ecology, rising quickly and maxing out at the carrying capacity of the environment. It’s an S-shaped curve that can take any real-valued number and map it into a value between 0 and 1, but never exactly at those limits.


* [K Nearest Neighbor](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/KNN%20Model)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/KNN.png)

K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique.It assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories and it stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm.
K-NN is a non-parametric algorithm, which means it does not make any assumption on underlying data.
It is also called a lazy learner algorithm because it does not learn from the training set immediately instead it stores the dataset and at the time of classification, it performs an action on the dataset.KNN algorithm at the training phase just stores the dataset and when it gets new data, then it classifies that data into a category that is much similar to the new data.


* [Naive Bayes](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Naive%20Bayes)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/Naive%20Bayes%20models.png)

Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other.


* [Support Vactor Machines](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/SVM)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/SVM.jpg)

A support vector machine (SVM) is a supervised machine learning model that uses classification algorithms for two-group classification problems. After giving an SVM model sets of labeled training data for each category, they’re able to categorize new text.


* [Decision Tree](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/DT)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/decision%20tree.png)

The decision tree Algorithm belongs to the family of supervised machine learning algorithms. It can be used for both a classification problem as well as for regression problem.The goal of this algorithm is to create a model that predicts the value of a target variable, for which the decision tree uses the tree representation to solve the problem in which the leaf node corresponds to a class label and attributes are represented on the internal node of the tree.


* [Decision Tree](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Random_forest)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/random%20forest.jpg)

Random forest is a flexible, easy to use machine learning algorithm that produces, even without hyper-parameter tuning, a great result most of the time. It is also one of the most used algorithms, because of its simplicity and diversity (it can be used for both classification and regression tasks). In this post we'll learn how the random forest algorithm works, how it differs from other algorithms and how to use it.


* [Ensemble Techniques](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/tree/main/Ensemble)

![Alt Text](https://github.com/piyushpathak03/Machine-learning-algorithm-PDF/blob/main/static/Ensemble%20techniques.png)

 Ensemble methods is a machine learning technique that combines several base models in order to produce one optimal predictive model. To better understand this definition lets take a step back into ultimate goal of machine learning and model building. This is going to make more sense as I dive into specific examples and why Ensemble methods are used.



## About me

**Piyush Pathak**

[**PORTFOLIO**](https://anirudhrapathak3.wixsite.com/piyush)

[**GITHUB**](https://github.com/piyushpathak03)

[**BLOG**](https://medium.com/@piyushpathak03)


# 📫 Follw me: 

[![Linkedin Badge](https://img.shields.io/badge/-PiyushPathak-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/piyushpathak03/)](https://www.linkedin.com/in/piyushpathak03/)

<p  align="right"><img height="100" src = "https://media.giphy.com/media/l3URDstnIjBNY7rwLB/giphy.gif"></p>
