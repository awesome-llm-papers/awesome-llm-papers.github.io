---
layout: publication
title: Atomic Consistency Preference Optimization For Long-form Question Answering
authors: Chen et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2025
bibkey: chen2025atomic
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.09039'}]
tags: [Model Architecture, Training Techniques, Efficiency And Optimization, ACL,
  RAG, GPT, Datasets]
---
Large Language Models (LLMs) frequently produce factoid hallucinations - plausible yet incorrect answers. A common mitigation strategy is model alignment, which improves factual accuracy by training on curated factual and non-factual pairs. However, this approach often relies on a stronger model (e.g., GPT-4) or an external knowledge base to assess factual correctness, which may not always be accessible. To address this, we propose Atomic Consistency Preference Optimization (ACPO), a self-supervised preference-tuning method that enhances factual accuracy without external supervision. ACPO leverages atomic consistency signals, i.e., the agreement of individual facts across multiple stochastic responses, to identify high- and low-quality data pairs for model alignment. By eliminating the need for costly GPT calls, ACPO provides a scalable and efficient approach to improving factoid question-answering. Despite being self-supervised, empirical results demonstrate that ACPO outperforms FactAlign, a strong supervised alignment baseline, by 1.95 points on the LongFact and BioGen datasets, highlighting its effectiveness in enhancing factual reliability without relying on external models or knowledge bases.