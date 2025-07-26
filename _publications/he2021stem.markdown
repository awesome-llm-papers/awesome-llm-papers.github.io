---
layout: publication
title: 'The Stem Cell Hypothesis: Dilemma Behind Multi-task Learning With Transformer
  Encoders'
authors: Han He, Jinho D. Choi
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: he2021stem
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.06939'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Han He, Jinho D. Choi
---
Multi-task learning with transformer encoders (MTL) has emerged as a powerful
technique to improve performance on closely-related tasks for both accuracy and
efficiency while a question still remains whether or not it would perform as
well on tasks that are distinct in nature. We first present MTL results on five
NLP tasks, POS, NER, DEP, CON, and SRL, and depict its deficiency over
single-task learning. We then conduct an extensive pruning analysis to show
that a certain set of attention heads get claimed by most tasks during MTL, who
interfere with one another to fine-tune those heads for their own objectives.
Based on this finding, we propose the Stem Cell Hypothesis to reveal the
existence of attention heads naturally talented for many tasks that cannot be
jointly trained to create adequate embeddings for all of those tasks. Finally,
we design novel parameter-free probes to justify our hypothesis and demonstrate
how attention heads are transformed across the five tasks during MTL through
label analysis.