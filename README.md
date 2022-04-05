# Decision-Tree-Iris_Dataset
This is a practice notebook, focused towards learning more about Decision Tree model. 
Quick overview of Decision Tree Algorithm and how it works:
Decision Tree is a Supervised Machine Learning Algorithm that uses a set of rules to make decisions, similarly to how humans make decisions. 
Decision trees can perform both classification and regression tasks, are also refered to as CART algorithm: Classification and Regression Tree. 
(an umbrella term, applicable to all tree-based algorithms, not just decision trees). 
The intuition behind Decision Trees is that we use the dataset features to create yes/no questions and continually split the dataset until we isolate all data points belonging to each class.
With this process we can organize the data in a tree structure.
Every time we ask a question we’re adding a node to the tree. The first node is called the root node.
The result of asking a question splits the dataset based on the value of a feature, and creates new nodes.
If we decide to stop the process after a split, the last nodes created are called leaf nodes.
The deeper topic I always wanted to explore is: How does decision tree decide where to split. 
A one line answer to this: A point which minimize the loss function is chosen for the split. 
And how is this loss function chosen? 
Using 
1. Gini Impurity : Gini Impurity is measure of variance across the different classes[1]
2. Enthropy : Entropy is a measure of chaos within the node. And chaos, in the context of decision trees, is having a node where all classes are equally present in the data.
