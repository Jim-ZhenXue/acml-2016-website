.. title: Tutorials
.. slug: tutorials
.. date: 2015-12-10 10:09:17 UTC+13:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

.. contents::


Recent Advances in Distributed Machine Learning
===============================================

**Taifeng Wang, Wei Chen**

In recent years, artificial intelligence has demonstrated its power in many
important applications. Besides the novel machine learning algorithms (e.g.,
deep neural networks), their distributed implementations play a very
critical role in these successes. In this tutorial, we will first review
popular machine learning models and their corresponding optimization
techniques. Second, we will introduce different ways of parallelizing machine
learning algorithms, i.e., data parallelism, model parallelism, synchronous
parallelism, asynchronous parallelism, and so on, and discuss their theoretical
properties, advantages, and limitations. Third, we will discuss some recent
research works that try to overcome the limitations of standard parallelization
mechanisms, including advanced asynchronous parallelism and new communication
and aggregation methods. Finally, we will introduce how to leverage popular
distributed machine learning platforms, such as Spark MlLib, DMTK, Tensorflow,
to parallelize a given machine learning algorithm, in order to give the
audience some practical guidelines on this topic.


Bayesian Nets from the ground up
================================

**Aish Fenton**

In this tutorial Aish will take us through Bayesian Networks (i.e. Directed
Graphical Models) from the ground up. Many real-world problems in machine
learning benefit from building custom models and explicitly stating your
distributional assumptions. Graphical models provide a general methodology for
doing this. They’ve found success in such diverse settings as bioinformatics,
speech processing, and driving parts of Netflix’s recommendation engine.
Aish will start from the basics and build up to more advanced concepts, such as
bayesian nonparametric extensions. By the end of the tutorial you should have a
gasp on the theory underpinning Bayes nets, how to build your own models, and
how to infer them. 


Mass Estimation: Enabling density-based or distance-based algorithms to do what they cannot do
==============================================================================================

**Kai Ming Ting**

This tutorial provides an overview of mass estimation, an alternative data
modelling mechanism to density estimation; and details how it can overcome
fundamental weaknesses of density-based or distance-based algorithms to enable
them to do what they cannot do previously.

Mass estimation is attractive because the basic measure, mass, is not only more
fundamental than density, but also more versatile---mass can be used to do
density estimation, as a means for subspace selection and to find
multi-dimensional median, and can be extended to measure dissimilarity of any
two points. Example advantages of mass over density or distance are given as
follows:

* DEMass--Density estimator based on mass--runs orders of magnitude faster than
  kernel and kNN density estimators
* Mass has been used, in place of density, as an effective means for subspace
  selection.
* Half-space mass is the maximally robust and efficient method to find
  multi-dimensional median. Existing methods such as data depth are either less
  robust or computationally more expensive.
* Simply replacing mass-based dissimilarity (a data dependent measure) with
  distance measure (a data independent measure) overcomes key weaknesses of
  density-based and distance-based methods in clustering, anomaly detection,
  information retrieval and classification.

This tutorial draws upon recent work on mass estimation and previous work which was also mass- based but was incorrectly categorised as density-based.


Deep Approaches to Semantic Matching for Text
=============================================

**Yanyan Lan, Jiafeng Guo, Jun Xu**

Semantic matching is critical in many text applications, including paraphrase
identification, information retrieval, question answering, and machine
translation. A variety of machine learning techniques have been developed for
various semantic matching tasks, referred to as “learning to match”. Recently,
deep learning approaches have shown their effectiveness in this area, and a
number of methods have been proposed from different aspects of matching. In
this tutorial, we will give a systematic and detailed survey on newly developed
deep learning technologies for semantic matching. We will focus on the
descriptions on the fundamental problems, as well as the novel solutions from
bridging the word level semantic gap and conducting sentence level end-to-end
semantic matching. We will also discuss the potential applications and future
directions of semantic matching for text.


