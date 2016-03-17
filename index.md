---
layout: post
title: Contents
---
{% newthought 'These notes'%} form a concise introductory course on probabilistic graphical modeling{% sidenote 1 'Probabilistic graphical modeling is a subfield of AI that studies how to model the world with probability distributions.'%}.
They accompany and are based on the material of [CS228](http://cs.stanford.edu/~ermon/cs228/index.html), the graphical models course at Stanford University, taught by [Stefano Ermon](http://cs.stanford.edu/~ermon/).

This site is currently under construction, but come back soon as we get more material online.
In the meantime, contact [Volodymyr Kuleshov](http://www.stanford.edu/~kuleshov) with any feedback and feel free to contribute your improvements on [Github](https://github.com/kuleshov/cs228-notes).

## Preliminaries

1. [Introduction](preliminaries/introduction/) What is probabilistic graphical modeling? Overview of the course.

2. Review of probability theory: Probability distributions. Conditional probability. Random variables.

2. Examples of real-world applications: Image denoising. RNA structure prediciton. Lexical analyses of sentences. Optical character recogition.

## Representation

1. [Bayesian networks](representation/directed/): Definitions. Representations via directed graphs. Independencies in directed models.

2. [Markov random fields](representation/undirected/): Undirected vs directed models. Independencies in undirected models. Conditional random fields.

## Inference

1. [Variable elimination](inference/ve/) The inference problem. Variable elimination. Complexity of inference.

2. [Belief propagation](inference/jt/): The junction tree algorithm. Exact inference in arbitrary graphs. Loopy Belief Propagation.

3. [Sampling-based inference](inference/sampling/): Monte-Carlo sampling. Importance sampling. Markov Chain Monte-Carlo. Applications in inference.

## Learning

1. Learning in directed models: Undirected graphs. Independencies in undirected models. Conditional random fields.

2. Learning in undirected models: Undirected graphs. Independencies in undirected models. Conditional random fields.

3. Structure learning: Undirected graphs. Independencies in undirected models. Conditional random fields.
