---
layout: publication
title: 'Smoothing Out Hallucinations: Mitigating LLM Hallucination With Smoothed Knowledge
  Distillation'
authors: Nguyen et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2025
bibkey: nguyen2025smoothing
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.11306'}]
tags: [Distillation, Training Techniques, Efficiency And Optimization, Evaluation,
  ACL, EMNLP, Applications, RAG, Datasets]
---
Large language models (LLMs) often suffer from hallucination, generating
factually incorrect or ungrounded content, which limits their reliability in
high-stakes applications. A key factor contributing to hallucination is the use
of hard labels during training, which enforce deterministic supervision,
encourage overconfidence, and disregard the uncertainty inherent in natural
language. To address this, we propose mitigating hallucination through
knowledge distillation (KD), where a teacher model provides smoothed soft
labels to a student model, reducing overconfidence and improving factual
grounding. We apply KD during supervised finetuning on instructional data,
evaluating its effectiveness across LLMs from different families. Experimental
results on summarization benchmarks demonstrate that KD reduces hallucination
compared to standard finetuning while preserving performance on general NLP
tasks. These findings highlight KD as a promising approach for mitigating
hallucination in LLMs and improving model reliability.