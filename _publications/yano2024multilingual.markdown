---
layout: publication
title: 'Multilingual Sentence-t5: Scalable Sentence Encoders For Multilingual Applications'
authors: Yano et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2024
bibkey: yano2024multilingual
citations: 122
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.17528'}]
tags: [ACL, Reinforcement Learning, Fine Tuning, Applications]
---
Prior work on multilingual sentence embedding has demonstrated that the
efficient use of natural language inference (NLI) data to build
high-performance models can outperform conventional methods. However, the
potential benefits from the recent ``exponential'' growth of language models
with billions of parameters have not yet been fully explored. In this paper, we
introduce Multilingual Sentence T5 (m-ST5), as a larger model of NLI-based
multilingual sentence embedding, by extending Sentence T5, an existing
monolingual model. By employing the low-rank adaptation (LoRA) technique, we
have achieved a successful scaling of the model's size to 5.7 billion
parameters. We conducted experiments to evaluate the performance of sentence
embedding and verified that the method outperforms the NLI-based prior
approach. Furthermore, we also have confirmed a positive correlation between
the size of the model and its performance. It was particularly noteworthy that
languages with fewer resources or those with less linguistic similarity to
English benefited more from the parameter increase. Our model is available at
https://huggingface.co/pkshatech/m-ST5.