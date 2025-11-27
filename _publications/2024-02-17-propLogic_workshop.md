---
title: "How Transformers Reason: A Case Study on a Synthetic Propositional Logic Problem"
collection: publications
category: manuscripts
permalink: /publication/2024-02-17-propLogic_workshop
excerpt: '**Guanzhe Hong**, Nishanth Dikkala, Enming Luo, Cyrus Rashtchian, Xin Wang, Rina Panigrahy'
date: 2024-10-21
venue: 'NeurIPS MATH-AI Workshop'
paperurl: 'https://openreview.net/forum?id=kXXsqGiVnl'
---

Large language models (LLMs) have demonstrated remarkable performance in tasks that require reasoning abilities. Motivated by recent works showing evidence of LLMs being able to plan and reason on abstract reasoning problems in context, we conduct a set of controlled experiments on a synthetic propositional logic problem to provide a mechanistic understanding of how such abilities arise. In particular, for a decoder-only Transformer trained solely on our synthetic dataset, we identify the specific mechanisms by which a three-layer Transformer solves the reasoning task. In particular, we identify certain "planning" and "reasoning" circuits which require cooperation between the attention blocks to in totality implement the desired reasoning algorithm. To expand our findings, we then study a larger model, Mistral 7B. Using activation patching, we characterize internal components that are critical in solving our logic problem. Overall, our work systemically uncovers novel aspects of small and large transformers, and continues the study of how they plan and reason.
