---
layout: publication
title: 'Teaching Pretrained Models With Commonsense Reasoning: A Preliminary Kb-based
  Approach'
authors: Li Shiyang, Chen Jianshu, Yu Dian
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: li2019teaching
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.09743'}]
tags: [RAG, EMNLP, Training Techniques, BERT, Model Architecture, Few Shot]
---
Recently, pretrained language models (e.g., BERT) have achieved great success
on many downstream natural language understanding tasks and exhibit a certain
level of commonsense reasoning ability. However, their performance on
commonsense tasks is still far from that of humans. As a preliminary attempt,
we propose a simple yet effective method to teach pretrained models with
commonsense reasoning by leveraging the structured knowledge in ConceptNet, the
largest commonsense knowledge base (KB). Specifically, the structured knowledge
in KB allows us to construct various logical forms, and then generate
multiple-choice questions requiring commonsense logical reasoning. Experimental
results demonstrate that, when refined on these training examples, the
pretrained models consistently improve their performance on tasks that require
commonsense reasoning, especially in the few-shot learning setting. Besides, we
also perform analysis to understand which logical relations are more relevant
to commonsense reasoning.