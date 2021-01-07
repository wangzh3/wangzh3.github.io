---
layout:     post
title:      Automated reasoning
subtitle:   
date:       2020-10-28
author:     Zihao Wang
header-img: img/post-bg-desk.jpg
catalog: true
tags:
    - 
---

## Evaluation of Axiom Selection Techniques

Automated theorem proving (ATP) is concerned with the development and use of systems that automated sound reasoning: the derivation of conclusions that follow inevitably from facts. However, the search complexity for finding proofs of theorems is enormous. To tackle this challenge, this research uses artificial intelligence methods to extract a small subset of axioms sufficient for proving that a given conjecture is a theorem. Machine learning algorithms combined with search strategies are achieved for axiom selection. The experimental results demonstrate that the performance of the local beam search is high than the baseline and it has the best evaluation indices. Therefore, it is a promising algorithm. 

>The research paper is published on the 7th workshop on practical aspects of automated reasoning in 2020, directed by Professor Dr. Geoff Sutcliffe.

Paper: Liu. Q, Wu. Z, Wang. Z, and Sutcliffe. G, “Evaluation of Axiom Selection Techniques,” in PAAR 2020: Seventh Workshop on Practical Aspects of Automated Reasoning, Paris, France, Jun. 2020, p. 13.

The research paper is [here](http://ceur-ws.org/Vol-2752/paper5.pdf). The details of the algorithms in Machine learning algorithms combined with search strategies are [here](https://github.com/wangzh3/My-axiom-selection/blob/main/algorithm.pdf).

The graph search python framework that is implemented by myself is [here](https://github.com/wangzh3/My-axiom-selection).

Here is a sample of graph search:

![](https://github.com/wangzh3/wangzh3.github.io/blob/master/upload/axiom%20tree.png?raw=true)