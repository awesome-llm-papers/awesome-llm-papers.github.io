---
layout: publication
title: 'Promptner: Prompting For Named Entity Recognition'
authors: Dhananjay Ashok, Zachary C. Lipton
conference: Arxiv
year: 2023
citations: 17
bibkey: ashok2023prompting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.15444'}]
tags: [Fine-Tuning, RAG, Few-Shot, Interpretability and Explainability, Reinforcement
    Learning, Prompting, Training Techniques]
---
In a surprising turn, Large Language Models (LLMs) together with a growing
arsenal of prompt-based heuristics now offer powerful off-the-shelf approaches
providing few-shot solutions to myriad classic NLP problems. However, despite
promising early results, these LLM-based few-shot methods remain far from the
state of the art in Named Entity Recognition (NER), where prevailing methods
include learning representations via end-to-end structural understanding and
fine-tuning on standard labeled corpora. In this paper, we introduce PromptNER,
a new state-of-the-art algorithm for few-Shot and cross-domain NER. To adapt to
any new NER task PromptNER requires a set of entity definitions in addition to
the standard few-shot examples. Given a sentence, PromptNER prompts an LLM to
produce a list of potential entities along with corresponding explanations
justifying their compatibility with the provided entity type definitions.
Remarkably, PromptNER achieves state-of-the-art performance on few-shot NER,
achieving a 4% (absolute) improvement in F1 score on the ConLL dataset, a 9%
(absolute) improvement on the GENIA dataset, and a 4% (absolute) improvement on
the FewNERD dataset. PromptNER also moves the state of the art on Cross Domain
NER, outperforming prior methods (including those not limited to the few-shot
setting), setting a new mark on 3/5 CrossNER target domains, with an average F1
gain of 3%, despite using less than 2% of the available data.