# DecisionTrees

Supervised Technique tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome.

Entropy: Entropy is a metric to measure the impurity in a given attribute. It specifies randomness in data. Entropy can be calculated as:

Entropy(s)= -P(yes)log2 P(yes)- P(no) log2 P(no)
Where,

S= Total number of samples
P(yes)= probability of yes
P(no)= probability of no


Information Gain:
Information gain is the measurement of changes in entropy after the segmentation of a dataset based on an attribute.
It calculates how much information a feature provides us about a class.
According to the value of information gain, we split the node and build the decision tree.
A decision tree algorithm always tries to maximize the value of information gain, and a node/attribute having the highest information gain is split first. It can be calculated using the below formula:
Information Gain= Entropy(S)- {(Weighted Avg) *Entropy(each feature)}


Gini Index:
Gini index is a measure of impurity or purity used while creating a decision tree in the CART(Classification and Regression Tree) algorithm.
An attribute with the low Gini index should be preferred as compared to the high Gini index.
It only creates binary splits, and the CART algorithm uses the Gini index to create binary splits.

Gini Index= 1- ∑jPj2


The maximum value for entropy is 1 whereas the maximum value for Gini impurity is 0.5.

Pruning is a process of deleting the unnecessary nodes from a tree in order to get the optimal decision tree.


https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm
https://towardsdatascience.com/decision-tree-in-machine-learning-e380942a4c96


