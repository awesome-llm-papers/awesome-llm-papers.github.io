---
layout: publication
title: 'Birds Have Four Legs?! Numersense: Probing Numerical Commonsense Knowledge
  Of Pre-trained Language Models'
authors: Bill Yuchen Lin, Seyeon Lee, Rahul Khanna, Xiang Ren
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: lin2020birds
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00683'}]
tags: ["EMNLP"]
short_authors: Lin et al.
---
Recent works show that pre-trained language models (PTLMs), such as BERT,
possess certain commonsense and factual knowledge. They suggest that it is
promising to use PTLMs as "neural knowledge bases" via predicting masked words.
Surprisingly, we find that this may not work for numerical commonsense
knowledge (e.g., a bird usually has two legs). In this paper, we investigate
whether and to what extent we can induce numerical commonsense knowledge from
PTLMs as well as the robustness of this process. To study this, we introduce a
novel probing task with a diagnostic dataset, NumerSense, containing 13.6k
masked-word-prediction probes (10.5k for fine-tuning and 3.1k for testing). Our
analysis reveals that: (1) BERT and its stronger variant RoBERTa perform poorly
on the diagnostic dataset prior to any fine-tuning; (2) fine-tuning with
distant supervision brings some improvement; (3) the best supervised model
still performs poorly as compared to human performance (54.06% vs 96.3% in
accuracy).