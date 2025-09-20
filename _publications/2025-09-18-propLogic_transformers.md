---
title: "A Implies B: Circuit Analysis in LLMs for Propositional Logical Reasoning"
collection: publications
category: manuscripts
permalink: /publication/2025-09-18-propLogic_transformers
excerpt: '**Guanzhe Hong**, Nishanth Dikkala, Enming Luo, Cyrus Rashtchian, Xin Wang, Rina Panigrahy'
date: 2025-09-18
venue: 'NeurIPS 2025 (Spotlight)'
paperurl: 'https://arxiv.org/abs/2411.04105'
---

Due to the size and complexity of modern large language models (LLMs), it has proven challenging to uncover the underlying mechanisms that models use to solve reasoning problems. For instance, is their reasoning for a specific problem localized to certain parts of the network? Do they break down the reasoning problem into modular components that are then executed as sequential steps as we go deeper in the model? To better understand the reasoning capability of LLMs, we study a minimal propositional logic problem that requires combining multiple facts to arrive at a solution. By studying this problem on Mistral and Gemma models, up to 27B parameters, we illuminate the core components the models use to solve such logic problems. From a mechanistic interpretability point of view, we use causal mediation analysis to uncover the pathways and components of the LLMs' reasoning processes. Then, we offer fine-grained insights into the functions of attention heads in different layers. We not only find a sparse circuit that computes the answer, but we decompose it into sub-circuits that have four distinct and modular uses. Finally, we reveal that three distinct models -- Mistral-7B, Gemma-2-9B and Gemma-2-27B -- contain analogous but not identical mechanisms.

[Paper link](https://arxiv.org/abs/2411.04105) 
