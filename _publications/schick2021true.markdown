---
layout: publication
title: True Few-shot Learning With Prompts -- A Real-world Perspective
authors: "Timo Schick, Hinrich Sch\xFCtze"
conference: Transactions of the Association for Computational Linguistics
year: 2021
citations: 20
bibkey: schick2021true
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.13440'}]
tags: [Few-Shot, Applications, Reinforcement Learning, Prompting, Evaluation]
---
Prompt-based approaches are strong at few-shot learning. However, Perez et
al. (2021) have recently cast doubt on their performance because they had
difficulty getting good results in a "true" few-shot setting in which prompts
and hyperparameters cannot be tuned on a dev set. In view of this, we conduct
an extensive study of PET, a method that combines textual instructions with
example-based finetuning. We show that, if correctly configured, PET performs
strongly in a true few-shot setting, i.e., without a dev set. Crucial for this
strong performance is PET's ability to intelligently handle multiple prompts.
We then put our findings to a real-world test by running PET on RAFT, a
benchmark of tasks taken directly from realistic NLP applications for which no
labeled dev or test sets are available. PET achieves a new state of the art on
RAFT and performs close to non-expert humans for 7 out of 11 tasks. These
results demonstrate that prompt-based learners like PET excel at true few-shot
learning and underpin our belief that learning from instructions will play an
important role on the path towards human-like few-shot learning capabilities.