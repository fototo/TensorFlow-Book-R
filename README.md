Machine Learning with TensorFlow(R version)
================

[This](https://github.com/haven-jeon/TensorFlow-Book-R) is the unofficial code repository for [Machine Learning with TensorFlow](http://www.tensorflowbook.com/) with **R**.

This repository may contain different experiment R code.

이 저장소는 R 텐서플로기반 텐서플로 모형작성 연습을 하기 위한 곳입니다. R만의 장점을 가질수 있는 부분이 있음을 개인적으로 코드작성을 통해 알아기기 위한 목적으로 작성되었으며, 책의 코드에서 부분적으로 개선되거나 실험된 코드/메모가 포함될 수 있음을 알려드립니다.(예: [CNN model view](https://github.com/haven-jeon/TensorFlow-Book-R/blob/master/ch09_cnn/Concept04_cifar.md) )

TODO
====

-   예제 코드 완성
-   R Reference Class 기반 코드 재활용성 개선
-   GAN 모듈 추가

Requirement
===========

-   [TensorFlow](https://www.tensorflow.org/) (&gt;= 1.0)
-   [Python](https://www.python.org/) (&gt;= 3.4)
-   [tensorflow](https://cran.r-project.org/package=tensorflow) (&gt;= 0.7)
-   [reticulate](https://cran.r-project.org/package=reticulate) (&gt;= 0.7)

Summary
=======

[Chapter 2](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch02_basics) - TensorFlow Basics
--------------------------------------------------------------------------------------------------------

-   **Concept 1**: Defining tensors
-   **Concept 2**: Evaluating ops
-   **Concept 3**: Interactive session
-   **Concept 4**: Session loggings
-   **Concept 5**: Variables
-   **Concept 6**: Saving variables
-   **Concept 7**: Loading variables
-   **Concept 8**: TensorBoard

[Chapter 3](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch03_regression) - Regression
-----------------------------------------------------------------------------------------------------

-   **Concept 1**: Linear regression
-   **Concept 2**: Polynomial regression
-   **Concept 3**: Regularization

[Chapter 4](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch04_classification) - Classification
-------------------------------------------------------------------------------------------------------------

-   **Concept 1**: Linear regression for classification
-   **Concept 2**: Logistic regression
-   **Concept 3**: 2D Logistic regression
-   **Concept 4**: Softmax classification

[Chapter 5](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch05_clustering) - Clustering (*working*)
-----------------------------------------------------------------------------------------------------------------

-   **Concept 1**: Clustering
-   **Concept 2**: Segmentation
-   **Concept 3**: Self-organizing map

[Chapter 6](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch06_hmm) - Hidden markov models
--------------------------------------------------------------------------------------------------------

-   **Concept 1**: Forward algorithm
-   **Concept 2**: Viterbi decode

[Chapter 7](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch07_autoencoder) - Autoencoders (*working*)
--------------------------------------------------------------------------------------------------------------------

-   **Concept 1**: Autoencoder
-   **Concept 2**: Applying an autoencoder to images
-   **Concept 3**: Denoising autoencoder

[Chapter 8](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch08_rl) - Reinforcement learning (*working*)
---------------------------------------------------------------------------------------------------------------------

-   **Concept 1**: Reinforcement learning

[Chapter 9](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch09_cnn) - Convolutional Neural Networks
-----------------------------------------------------------------------------------------------------------------

-   **Concept 1**: Using CIFAR-10 dataset
-   **Concept 2**: Convolutions
-   **Concept 3**: Convolutional neural network
-   **Concept 4**: Convolutional neural network model debugging(2), **Newly added**

[Chapter 10](https://github.com/haven-jeon/TensorFlow-Book-R/tree/master/ch10_rnn) - Recurrent Neural Network(*working*)
------------------------------------------------------------------------------------------------------------------------

-   **Concept 1**: Loading timeseries data
-   **Concept 2**: Recurrent neural networks
-   **Concept 3**: Applying RNN to real-world data for timeseries prediction
