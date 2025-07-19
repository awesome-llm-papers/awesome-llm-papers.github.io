---
layout: publication
title: Are Transformers Able To Reason By Connecting Separated Knowledge In Training
  Data?
authors: Yin Yutong, Wang Zhaoran
conference: Lecture Notes in Computer Science
year: 2025
bibkey: yin2025are
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.15857'}]
tags: [RAG, Training Techniques, Prompting, Transformer, Model Architecture, Few Shot,
  Reinforcement Learning]
---
Humans exhibit remarkable compositional reasoning by integrating knowledge from various sources. For example, if someone learns ( B = f(A) ) from one source and ( C = g(B) ) from another, they can deduce ( C=g(B)=g(f(A)) ) even without encountering ( ABC ) together, showcasing the generalization ability of human intelligence. In this paper, we introduce a synthetic learning task, "FTCT" (Fragmented at Training, Chained at Testing), to validate the potential of Transformers in replicating this skill and interpret its inner mechanism. In the training phase, data consist of separated knowledge fragments from an overall causal graph. During testing, Transformers must infer complete causal graph traces by integrating these fragments. Our findings demonstrate that few-shot Chain-of-Thought prompting enables Transformers to perform compositional reasoning on FTCT by revealing correct combinations of fragments, even if such combinations were absent in the training data. Furthermore, the emergence of compositional reasoning ability is strongly correlated with the model complexity and training-testing data similarity. We propose, both theoretically and empirically, that Transformers learn an underlying generalizable program from training, enabling effective compositional reasoning during testing.