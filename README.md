# Decision Tree Classification and Hyperparameter Tuning

## Overview

This project demonstrates the implementation of a Decision Tree Classifier using the Iris dataset in Scikit-Learn. The project includes theoretical concepts, mathematical calculations, hyperparameter tuning, and visualization of the trained Decision Tree.

## Objectives

* Understand the working of Decision Trees.
* Compare Information Gain and Gini Impurity.
* Perform Entropy, Information Gain, and Gini calculations.
* Study overfitting and pruning techniques.
* Train a Decision Tree model using the Iris dataset.
* Experiment with different hyperparameters.
* Visualize the trained Decision Tree.

## Dataset

The Iris dataset is used in this project. It is a built-in dataset available in the Scikit-Learn library.

## Hyperparameters Tested

The following hyperparameters were evaluated:

1. **max_depth**

   * Controls the maximum depth of the tree.
   * Helps prevent overfitting.

2. **min_samples_split**

   * Minimum number of samples required to split a node.
   * Controls tree complexity.

3. **ccp_alpha**

   * Used for Cost Complexity Pruning.
   * Removes unnecessary branches from the tree.

## Technologies Used

* Python
* Scikit-Learn
* Pandas
* Matplotlib
* Jupyter Notebook

## Results

The impact of different hyperparameters was analyzed using:

* Model Accuracy
* Tree Depth

A visualization of the trained Decision Tree was also generated to identify:

* Root Node
* Leaf Nodes
* Samples
* Value

## Conclusion

Decision Trees are simple and effective machine learning algorithms for classification and regression tasks. Hyperparameter tuning and pruning techniques help improve model performance and reduce overfitting.

