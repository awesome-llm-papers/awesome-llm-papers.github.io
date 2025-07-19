---
layout: publication
title: 'Explanation Sensitivity To The Randomness Of Large Language Models: The Case
  Of Journalistic Text Classification'
authors: Bogaert et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2024
bibkey: bogaert2024explanation
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.05085'}]
tags: [Model Architecture, Interpretability And Explainability, Training Techniques,
  BERT, ACL, EMNLP]
---
Large language models (LLMs) perform very well in several natural language
processing tasks but raise explainability challenges. In this paper, we examine
the effect of random elements in the training of LLMs on the explainability of
their predictions. We do so on a task of opinionated journalistic text
classification in French. Using a fine-tuned CamemBERT model and an explanation
method based on relevance propagation, we find that training with different
random seeds produces models with similar accuracy but variable explanations.
We therefore claim that characterizing the explanations' statistical
distribution is needed for the explainability of LLMs. We then explore a
simpler model based on textual features which offers stable explanations but is
less accurate. Hence, this simpler model corresponds to a different tradeoff
between accuracy and explainability. We show that it can be improved by
inserting features derived from CamemBERT's explanations. We finally discuss
new research directions suggested by our results, in particular regarding the
origin of the sensitivity observed in the training randomness.