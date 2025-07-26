---
layout: publication
title: Context-guided BERT For Targeted Aspect-based Sentiment Analysis
authors: Zhengxuan Wu, Desmond C. Ong
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: wu2020context
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.07523'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Zhengxuan Wu, Desmond C. Ong
---
Aspect-based sentiment analysis (ABSA) and Targeted ASBA (TABSA) allow
finer-grained inferences about sentiment to be drawn from the same text,
depending on context. For example, a given text can have different targets
(e.g., neighborhoods) and different aspects (e.g., price or safety), with
different sentiment associated with each target-aspect pair. In this paper, we
investigate whether adding context to self-attention models improves
performance on (T)ABSA. We propose two variants of Context-Guided BERT
(CG-BERT) that learn to distribute attention under different contexts. We first
adapt a context-aware Transformer to produce a CG-BERT that uses context-guided
softmax-attention. Next, we propose an improved Quasi-Attention CG-BERT model
that learns a compositional attention that supports subtractive attention. We
train both models with pretrained BERT on two (T)ABSA datasets: SentiHood and
SemEval-2014 (Task 4). Both models achieve new state-of-the-art results with
our QACG-BERT model having the best performance. Furthermore, we provide
analyses of the impact of context in the our proposed models. Our work provides
more evidence for the utility of adding context-dependencies to pretrained
self-attention-based language models for context-based natural language tasks.