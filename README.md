# AN EMPIRICAL ANALYSIS OF PHISHING WEBSITE DETECTION FROM URLS USING MACHINE LEARNING TECHNIQUES

The phishing technique in the context of classification, where phishing websites are considered to involve automatically categorizing websites into a predetermined set of class values based on several features and a class variable. ML-based phishing techniques depend on website features to gather the information that can help classify websites to detect phishing sites. The problem of phishing cannot be eradicated, but it can be reduced by combating it in two ways, by improving targeted anti-phishing practices and techniques and by informing the public about how to detect and identify fraudulent phishing sites. To combat the ever-evolving and complex phishing attacks and tactics, ML anti-phishing techniques are essential.

In recent times, phishing websites are growing rapidly and causing more harm to users and organizations. It is becoming the biggest threat to people's daily life and network environment. In these attacks, the intruder acts as if it were a trusted organization with the intention of stealing responsible and essential information. A phishing website is a fake website that looks similar but differs in its destination. Unsuspecting users post their data believing that these websites are from trusted financial institutions. Thus, there is a need for an effective mechanism to detect phishing websites. In our project, we have developed a model that can be mainly used in determining whether websites are phishing or legitimate using URL feature extraction techniques. These features are compared with the features present in the feature extraction dataset and validated accordingly. Here in our project, we applied algorithms like Logistic Regression, Naive Bayes, Support vector Machine and Random Forest Classifier to the model that was developed. During testing, it was observed that the system worked well and as expected. This paper aims to improve the detection method for detecting phishing websites using machine learning technology. In the future, a hybrid technology will be implemented for more accurate detection of phishing sites, for which the random forest algorithm of machine learning technology and the blacklist method will be used


## ALGORITHMS 

1) LOGISTIC REGRESSION
  	Logistic regression is a type of predictive analysis where phishing URLs can be detected based on attributes. In logistic regression, the input is given as training data and test data. Based on the given input, logistic regression is calculated using a regression function called a sigmoid function, with the calculated sigmoid function, the relationship between the training data and the test data is calculated. Based on the relationship, URLs are categorized as phishing or legitimate. If the patterns in the attributes of the training data and test data are the same, then the URLs are considered phishing URLs, and other URLs are considered legitimate URLs.
    
2) ANN
  	Inspired by biological neural networks, an artificial neural network (ANN) is a collection of interconnected nodes (neurons). Weights are usually assigned to each connection between nodes. The network learns by adjusting the weights in the learning phase for a correct prediction process. ANNs have been considered less suitable for data mining due to their poor interpretability and long training time. However, their advantages include the ability to classify patterns they have not been trained on and a high tolerance for data noise. In ANN we have used three hidden layers for training and fitting the data. The accuracy obtained by ANN is 88%. 
    
3) DECISION TREE
  	A Decision tree is a tree-like structure with attributes assigned as a node. Based on the values of the attribute’s algorithm will traverse through the tree finally ending with the leaves of the tree which contain classification output. In the Decision tree we are using the Gini index (It is a measure of the impurity of the values in the attributes and split the tree into many branches). Decision Tree models have rarely been experimented with to detect phishing URLs. Accuracy was comparatively lower with average performance and longer train and ride time. Fig5 is the decision tree for the dataset that has been collected. Red color nodes indicate that they are prone to phishing websites and blue color nodes indicate that they are legitimate websites. 
 
4) RANDOM FOREST CLASSIFIER
      Random forest classifier is a classification technique that uses algorithms consisting of many decision trees. It uses bagging and features randomness when building each individual tree to try to create an uncorrelated forest of trees whose prediction by committee is more accurate than that of any individual tree. 
      
5) NAÏVE BAYES
  	This classifier may also be known as a generative learning model. The classification here is based on the Bayes theorem ; it assumes independent predictors. Simply put, this classifier will assume that the existence of specific features in a class is unrelated to the existence of any other feature.  If there is a dependency between the properties on each other or on the presence of other properties, these will all be considered as making an independent contribution to the output probability. This classification algorithm is very useful for large data sets and is very easy to use. From the correlation graph, it is observed that most of the features are independent of each other. In that case, it is difficult to use the Naive Bayes algorithm for the classification is not an appropriate technique. The accuracy that we have obtained by using the Naive Bayes algorithm is 61%. 
    
6) SVM (SUPPORT VECTOR MACHINE)
Support vector machines (SVM) are used to classify both direct and non-linear data. In short, when the algorithm receives the original training data, it uses non-linear mapping to transfigure it into an advanced dimension. In this dimension, a direct optimal hyperactive airplane is sought to separate the data of any two classes. SVM can also be used for bracket and numerical validation. The simplest form of SVM is a two-class problem where the classes are linearly divisible. For a 2- D problem, a straight line can be drawn to separate the classes, in fact, multiple lines can be drawn. In the SVM algorithm, the kernels used for the classification of websites are Default, linear, RBF, and polynomial.
 
7) KNN
Learning for KNN classifiers takes place analogously, i.e., by comparing the test tuple with analogous training tuples. These are distance-grounded comparisons that basically assign equal weight to each trait; thus, delicacy may be low if noisy or inapplicable data is presented. Still, editing and trimming styles have been introduced to break the problem of gratuitous and noisy data tuples. The training tuples are described by n attributes. Each tuple represents a point in n-dimensional space. A good value for the number of neighbors can be determined experimentally
