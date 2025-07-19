---
layout: publication
title: 'Red Teaming Language Models To Reduce Harms: Methods, Scaling Behaviors, And
  Lessons Learned'
authors: Ganguli et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: ganguli2022red
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.07858'}]
tags: [EMNLP, Prompting, Agentic, Ethics And Bias, Reinforcement Learning, Security,
  Datasets]
---
We describe our early efforts to red team language models in order to
simultaneously discover, measure, and attempt to reduce their potentially
harmful outputs. We make three main contributions. First, we investigate
scaling behaviors for red teaming across 3 model sizes (2.7B, 13B, and 52B
parameters) and 4 model types: a plain language model (LM); an LM prompted to
be helpful, honest, and harmless; an LM with rejection sampling; and a model
trained to be helpful and harmless using reinforcement learning from human
feedback (RLHF). We find that the RLHF models are increasingly difficult to red
team as they scale, and we find a flat trend with scale for the other model
types. Second, we release our dataset of 38,961 red team attacks for others to
analyze and learn from. We provide our own analysis of the data and find a
variety of harmful outputs, which range from offensive language to more subtly
harmful non-violent unethical outputs. Third, we exhaustively describe our
instructions, processes, statistical methodologies, and uncertainty about red
teaming. We hope that this transparency accelerates our ability to work
together as a community in order to develop shared norms, practices, and
technical standards for how to red team language models.