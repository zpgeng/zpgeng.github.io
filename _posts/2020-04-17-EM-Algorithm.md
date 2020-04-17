---
layout: post
title:  "EM Algorithm Explained"
date:   2020-04-17
categories: Machine-Learning
comments: true

---

Recently, one of my favourite courses this semester mentioned a crucial concept in unsupervised clustering theory, which is widely known to all, *EM Algorithm*. This course is called *Computational Intelligence Lab*, which shows you a variety of AI-related problems and their corresponding solutions. It seems like an applied version course. However, I found it difficult to comprehend the whole underlying theory. It seems like this course always wants us to focus on the application part, but all of the previous foundation of the theory and their proof are omitted deliberately. Thus, I have to find so many off-class materials to fully understand the notion and concepts.

Anyway, let's now begin our journey to discover the key concepts of EM algorithm. 

# Why do we use EM algorithm?

It's the first question when we are learning machine learning concepts since we have to figure out why do we use them. The answer is trivial. First, we assume that there is an issue when we are computing the log-likelihood, which called **summation in logarithm**. To explain further, it is a phenomenon that when we are about to optimize the log-likelihood (Maximum Likelihood Estimation), we often **log** the original likelihood to simplify our calculations, since the product will become into the summation after logarithm calculation. However, in many cases, especially in Gaussian Mixture Model, the formula in the logarithm will be a summation. Thus, the optimization of XXX will soon become a "monster" which will be difficult to handle.

So we are introducing an additional variable called **latent variable**.

# (To be continued)