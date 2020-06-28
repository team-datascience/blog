---
id: MachineLearningIntroduction
title: MachineLearningIntroduction
sidebar_label: machinelearning
---


![Intro](assets/MachineLearning/intro.png)

Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it learn for themselves.


**How Machine Learning actually work**

Machine learning algorithms use computational methods to “learn” information directly from data without relying on a predetermined equation as a model. The algorithms adaptively improve their performance as the number of samples available for learning increases. Deep learning is a specialized form of machine learning.

**Applications of Machine Learning**

* Virtual Personal Assistants.

    eg: Alexa
* Predictions while Commuting. 
* Videos Surveillance. 
* Social Media Services.
* Email Spam and Malware Filtering.
* Online Customer Support.
* Search Engine Result Refining. 
* Product Recommendations.

**Real-life examples of Machine Learning**

* Image Recognition. 
* Speech Recognition.
* Medical diagnosis.
* Statistical Arbitrage. 
* Learning associations. 
* Classification.
* Prediction. 
* Extraction.

**Disadvantages of Machine Learning**

Machine Learning isn’t perfect,The following factors serve to limit it:

1. **Data Acquisition**

Machine Learning requires massive data sets to train on, and these should be inclusive/unbiased, and of good quality. There can also be times where they must wait for new data to be generated.

2. **Time and Resources**

ML needs enough time to let the algorithms learn and develop enough to fulfill their purpose with a considerable amount of accuracy and relevancy. It also needs massive resources to function. This can mean additional requirements of computer power for you.


## **Types of machine learning Algorithms**

Basically, algorithms play an important role in Machine Learning: On the one hand, they are responsible for recognizing patterns and on the other hand, they can generate solutions. Algorithms can be divided into different categories:

* Supervised learning
* Unsupervised learning
* Partially/semi supervised learning
* Reinforcing learning

![ml](assets/MachineLearning/ml.png)

### **Supervised Machine Learning**

Supervised learning algorithms try to model relationships and dependencies between the target prediction output and the input features such that we can predict the output values for new data based on those relationships which it learned from the previous data sets.

![Supervised learning](assets/MachineLearning/sl.png)

Supervised learning problems can be further grouped into regression and classification problems.


**Classification:** 

The goal is to predict discrete values is called Classification.

eg: {1,0}, {True, False}, {spam, not spam}.


**Regression:**

The goal is to predict continuous values is called Regression 
eg: home prices.
 

**Some popular examples of supervised machine learning algorithms are:**

* Linear regression for regression problems.
* Random forest for classification and regression problems.
* Support vector machines for classification problems.


**List of Common Algorithms**

* Nearest Neighbor
* Naive Bayes
* Decision Trees
* Linear Regression
* Support Vector Machines (SVM)
* Neural Networks

**Applications of Supervised Learning**

Supervised Learning Algorithms are used in a variety of applications. Let’s go through some of the most well-known applications.


**BioInformatics**

This is one of the most well-known applications of Supervised Learning because most of us use it in our day-to-day lives. BioInformatics is the storage of Biological Information of us humans such as fingerprints, iris texture, earlobe and so on. Cellphones of today are capable of learning our biological information and are then able to authenticate us bringing up the security of the system. Smartphones such as iPhones, Google Pixel are capable of facial recognition while OnePlus, Samsung is capable of In-display finger recognition.

**Speech Recognition**

 This is the kind of application where you teach the algorithm about your voice and it will be able to recognize you. The most well-known real-world applications are virtual assistants such as Google Assistant and Siri, which will wake up to the keyword with your voice only.

**Spam Detection**

This application is used where the unreal or computer-based messages and E-Mails are to be blocked. G-Mail has an algorithm that learns the different keywords which could be fake such as “You are the winner of something” and so forth and blocks those messages directly. OnePlus Messages App gives the user the task of making the application learn which keywords need to be blocked and the app will block those messages with the keyword.

**Object-Recognition for Vision**

This kind of application is used when you need to identify something. You have a huge dataset which you use to teach your algorithm and this can be used to recognize a new instance. Raspberry Pi algorithms which detect objects are the most well-known example.

**Disadvantages of Supervised Learning**

Supervised Learning has a lot of challenges and disadvantages that you could face while working with these algorithms. 

* You could overfit your algorithm easily
* Good examples need to be used to train the data
* Computation time is very large for Supervised Learning
* Unwanted data could reduce the accuracy
* Pre-Processing of data is always a challenge

### **Unsupervised Machine Learning**

The goal for unsupervised learning is to model the underlying structure or distribution in the data in order to learn more about the data.

![unsupervised learning](assets/MachineLearning/ul.png)


Unsupervised learning problems can be further grouped into clustering and association problems.

**Clustering**

clustering is nothing but grouping  the  similar object into  groups.

![sample](assets/MachineLearning/sample.png)

**Clustering Types**

* Hierarchical clustering
* K-means clustering
* K-NN (k nearest neighbors)
* Principal Component Analysis
* Singular Value Decomposition
* Independent Component Analysis


**Association**

Association rule mining finds interesting associations and relationships among large sets of data items.

**Some popular examples of unsupervised learning algorithms are:**

* k-means for clustering problems.
 
* Apriori algorithm for association rule learning problems.

**Applications of unsupervised machine learning**

Some applications of unsupervised machine learning techniques are:

* Clustering automatically split the dataset into groups base on their similarities

* Anomaly detection can discover unusual data points in your dataset. It is useful for finding fraudulent transactions

* Association mining identifies sets of items which often occur together in your  dataset

* Latent variable models are widely used for data preprocessing. Like reducing the number of features in a dataset or decomposing the dataset into multiple components

**Disadvantages of Unsupervised Learning**

* You cannot get precise information regarding data sorting, and the output as data used in unsupervised learning is labeled and not known
* Less accuracy of the results is because the input data is not known and not labeled by people in advance. This means that the machine requires to do this itself.
* The spectral classes do not always correspond to informational classes.
* The user needs to spend time interpreting and label the classes which follow that classification.
* Spectral properties of classes can also change over time so you can't have the same class information while moving from one image to another.

### **Semi-supervised machine learning**

Semi-supervised machine learning is a combination of supervised and unsupervised machine learning methods.

**Applications of Semi-Supervised Learning**


**Speech Analysis**

Since labeling of audio files is a very intensive task, Semi-Supervised learning is a very natural approach to solve this problem.

**Internet Content Classification**

Labeling each webpage is an impractical and unfeasible process and thus uses Semi-Supervised learning algorithms. Even the Google search algorithm uses a variant of Semi-Supervised learning to rank the relevance of a webpage for a given query.

**Protein Sequence Classification:**

 Since DNA strands are typically very large in size, the rise of Semi-Supervised learning has been imminent in this field.

### **Reinforcement Learning**

Reinforcement Learning(RL) is a type of machine learning technique that enables an agent to learn in an interactive environment by trial and error using feedback from its own actions and experiences.

**Types of Reinforcement: There are two types of Reinforcement**

**Positive**

Positive Reinforcement is defined as when an event, occurs due to a particular behavior, increases the strength and the frequency of the behavior. In other words, it has a positive effect on behavior.

**Advantages of reinforcement learning are:**

* Maximizes Performance
* Sustain Change for a long period of time


**Disadvantages of reinforcement learning:**

Too much Reinforcement can lead to overload of states which can diminish the results

**Negative**

Negative Reinforcement is defined as strengthening of a behavior because a negative condition is stopped or avoided.

**Advantages of reinforcement learning:**

* Increases Behavior
* Provide defiance to minimum standard of performance

**Disadvantages of reinforcement learning:**

* It Only provides enough to meet up the minimum behavior

**Applications of Reinforcement Learning** 

* RL can be used in robotics for industrial automation.
* RL can be used in machine learning and data processing
* RL can be used to create training systems that provide custom instruction and materials according to the requirement of students.