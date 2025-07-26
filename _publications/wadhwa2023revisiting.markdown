---
layout: publication
title: Revisiting Relation Extraction In The Era Of Large Language Models
authors: Somin Wadhwa, Silvio Amir, Byron C. Wallace
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
bibkey: wadhwa2023revisiting
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.05003'}]
tags: ["Evaluation", "Few-Shot", "Fine-Tuning", "In Context Learning", "Model Architecture", "Prompting", "Training Techniques"]
short_authors: Somin Wadhwa, Silvio Amir, Byron C. Wallace
---
Relation extraction (RE) is the core NLP task of inferring semantic
relationships between entities from text. Standard supervised RE techniques
entail training modules to tag tokens comprising entity spans and then predict
the relationship between them. Recent work has instead treated the problem as a
*sequence-to-sequence* task, linearizing relations between entities as
target strings to be generated conditioned on the input. Here we push the
limits of this approach, using larger language models (GPT-3 and Flan-T5 large)
than considered in prior work and evaluating their performance on standard RE
tasks under varying levels of supervision. We address issues inherent to
evaluating generative approaches to RE by doing human evaluations, in lieu of
relying on exact matching. Under this refined evaluation, we find that: (1)
Few-shot prompting with GPT-3 achieves near SOTA performance, i.e., roughly
equivalent to existing fully supervised models; (2) Flan-T5 is not as capable
in the few-shot setting, but supervising and fine-tuning it with
Chain-of-Thought (CoT) style explanations (generated via GPT-3) yields SOTA
results. We release this model as a new baseline for RE tasks.