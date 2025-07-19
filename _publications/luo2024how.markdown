---
layout: publication
title: How To Understand "support"? An Implicit-enhanced Causal Inference Approach
  For Weakly-supervised Phrase Grounding
authors: Luo et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: luo2024how
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.19116'}]
tags: [RAG, Training Techniques, Evaluation, Reinforcement Learning, Multimodal Models,
  Datasets, Merging]
---
Weakly-supervised Phrase Grounding (WPG) is an emerging task of inferring the
fine-grained phrase-region matching, while merely leveraging the coarse-grained
sentence-image pairs for training. However, existing studies on WPG largely
ignore the implicit phrase-region matching relations, which are crucial for
evaluating the capability of models in understanding the deep multimodal
semantics. To this end, this paper proposes an Implicit-Enhanced Causal
Inference (IECI) approach to address the challenges of modeling the implicit
relations and highlighting them beyond the explicit. Specifically, this
approach leverages both the intervention and counterfactual techniques to
tackle the above two challenges respectively. Furthermore, a high-quality
implicit-enhanced dataset is annotated to evaluate IECI and detailed
evaluations show the great advantages of IECI over the state-of-the-art
baselines. Particularly, we observe an interesting finding that IECI
outperforms the advanced multimodal LLMs by a large margin on this
implicit-enhanced dataset, which may facilitate more research to evaluate the
multimodal LLMs in this direction.