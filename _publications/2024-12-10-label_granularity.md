---
title: "Why Fine-grained Labels in Pretraining Benefit Generalization"
collection: publications
category: manuscripts
permalink: /publication/2024-12-10-label_granularity
excerpt: '**Guanzhe Hong**, Yin Cui, Ariel Fuxman, Stanley Chan, Enming Luo'
date: 2024-10-01
venue: 'Transactions on Machine Learning Research'
paperurl: 'https://arxiv.org/abs/2410.23129'
---
Recent studies show that pretraining a deep neural network with fine-grained labeled data, followed by fine-tuning on coarse-labeled data for downstream tasks, often yields better generalization than pretraining with coarse-labeled data. While there is ample empirical evidence supporting this, the theoretical justification remains an open problem. This paper addresses this gap by introducing a "hierarchical multi-view" structure to confine the input data distribution. Under this framework, we prove that: 1) coarse-grained pretraining only allows a neural network to learn the common features well, while 2) fine-grained pretraining helps the network learn the rare features in addition to the common ones, leading to improved accuracy on hard downstream test samples. 

[Paper link](https://arxiv.org/abs/2410.23129)
