# machine-learning-nutsnbolts

> The nuts and bolts of machine learning and insights into its operations. Generated by DALL·E 3.

![DALL·E 2024-02-08 18 09 28 - Create a wide-format, detailed illustration that visualizes _The nuts and bolts of machine learning_ without including any characters or letters  This](https://github.com/esakik/machine-learning-nutsnbolts/assets/44774033/845c0482-d8e6-41c1-8d10-827289af28c8)

This repository aims to organize implementations of machine learning algorithms and demonstrate practical ways to apply or use machine learning models.
I initiated this project to refresh and reinforce my fading knowledge of previously learned concepts, deepen my understanding of various algorithms, and examine examples of their practical applications.

## Algorithms

Here is an overview of machine learning algorithms that are either currently implemented or planned for future implementation.
Additionally, this table presents supplementary materials I have prepared to revisit and strengthen my understanding of what I learned.

| Algorithms                                                                                      | Implementations from Scratch                                                                                                                                                                                                                                                                              | Supplementary Links                                                                                                                                                                                          |
|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Gradient descent                                                                                | [![Gradient descent](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esakik/machine-learning-nutsnbolts/blob/main/algorithms/optimization/gradient_descent.ipynb)                                                                                     | [Stepping into Mathematical Optimization: Exploring Gradient Descent](https://dev.to/esakik/exploring-gradient-descent-after-implementing-linear-regression-from-scratch-i4e)                                |
| Feature scaling (Standardization/Normalization)                                                 | [![Feature scaling (Standardization / Normalization)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esakik/machine-learning-nutsnbolts/blob/main/algorithms/preprocessing/feature_scaling.ipynb)                                                    | [Deciphering Standardization and Normalization: Understanding Feature Scaling Techniques](https://dev.to/esakik/deciphering-standardization-and-normalization-understanding-feature-scaling-techniques-1cf5) |
| Linear regression, Regularization                                                               | [![Linear regression / Regularization](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esakik/machine-learning-nutsnbolts/blob/main/algorithms/supervised/linear_regression.ipynb)                                                                    | [Brushing Up on Linear Regression in Python: Theory to Practice](https://dev.to/esakik/re-learn-linear-regression-in-python-from-theory-to-practice-277m)                                                    |
| Logistic regression for classification, Activation function (Sigmoid/Softmax), One-hot encoding | [![Logistic regression for classification / Activation function (Sigmoid / Softmax) / One-hot encoding](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esakik/machine-learning-nutsnbolts/blob/main/algorithms/supervised/logistic_regression.ipynb) | [Brushing Up on Logistic Regression in Python: Theory to Practice](https://dev.to/esakik/brushing-up-on-logistic-regression-in-python-theory-to-practice-5ef4)                                               |
| k-NN for classification                                                                         | [![k-NN for classification](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esakik/machine-learning-nutsnbolts/blob/main/algorithms/supervised/knn_classification.ipynb)                                                                              | [Brushing Up on k-NN for Classification in Python: Theory to Practice](https://dev.to/esakik/brushing-up-on-k-nn-for-classification-in-python-theory-to-practice-phm)                                        |
| Neural Network for classification                                                               | [![Neural Network for classification](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esakik/machine-learning-nutsnbolts/blob/main/algorithms/supervised/neural_network_classification.ipynb)                                                         |                                                                                                                                                                                                              |
| PCA for dimensionality reduction                                                                | [![PCA for dimensionality reduction](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esakik/machine-learning-nutsnbolts/blob/main/algorithms/unsupervised/pca_dimensionality_reduction.ipynb)                                                         |                                                                                                                                                                                                              |
| k-means for clustering                                                                          | [![k-means for clustering](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esakik/machine-learning-nutsnbolts/blob/main/algorithms/unsupervised/kmeans_clustering.ipynb)                                                                              |                                                                                                                                                                                                              |                                                                                                                                                                                                              |

## Examples

Below are practical examples demonstrating the application of machine learning algorithms to address real-world challenges, as well as insights into the operation of machine learning models.

| Example                        | Implementations | Supplementary Links |
|--------------------------------|-----------------|---------------------|
| NVIDIA Triton Inference Server |                 |                     |

### Prerequisites

To experiment with the examples, you will need to follow these installation and setup procedures:

| Library          | Setup Instructions             |
|------------------|--------------------------------|
| Pyenv            | https://github.com/pyenv/pyenv |
| Poetry           | https://python-poetry.org/docs |

#### Configuration of the Python version

Ensure that this version aligns with the version used in Poetry, then choose the appropriate version:

```shell
$ pyenv install 3.9
$ pyenv local 3.9
```

#### Install the required dependencies

The minor version depends on the version of the Python you have installed:

```shell
$ poetry env use ~/.pyenv/versions/3.9.17/bin/python3.9
$ poetry install
```
