---
title: "How Transformers Solve Propositional Logic Problems: A Mechanistic Analysis"
collection: publications
category: manuscripts
permalink: /publication/2024-12-10-propLogic_transformers
excerpt: '**Guanzhe Hong**, Nishanth Dikkala, Enming Luo, Cyrus Rashtchian, Xin Wang, Rina Panigrahy'
date: 2024-11-04
venue: 'arXiv Preprint'
paperurl: 'https://arxiv.org/abs/2411.04105v3'
---

When large language models (LLMs) use in-context learning (ICL) to solve a new task, they seem to grasp not only the goal of the task but also core, latent concepts in the demonstration examples. This begs the question of whether transformers represent latent structures as part of their computation or whether they take shortcuts to solve the problem. Prior mechanistic work on ICL does not address this question because it does not sufficiently examine the relationship between the learned representation and the latent concept, and the considered problem settings often involve only single-step reasoning. In this work, we examine how transformers disentangle and use latent concepts. We show that in 2-hop reasoning tasks with a latent, discrete concept, the model successfully identifies the latent concept and does step-by-step concept composition. In tasks parameterized by a continuous latent concept, we find low-dimensional subspaces in the representation space where the geometry mimics the underlying parameterization. Together, these results refine our understanding of ICL and the representation of transformers, and they provide evidence for highly localized structures in the model that disentangle latent concepts in ICL tasks.

[Paper link](https://arxiv.org/abs/2506.16975)
