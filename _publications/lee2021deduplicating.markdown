---
layout: publication
title: Deduplicating Training Data Makes Language Models Better
authors: Lee et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2021
bibkey: lee2021deduplicating
citations: 162
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.06499'}]
tags: [Prompting, Tools, Training Techniques, Evaluation, ACL, Datasets, Reinforcement
    Learning, Language Modeling]
---
We find that existing language modeling datasets contain many near-duplicate
examples and long repetitive substrings. As a result, over 1% of the unprompted
output of language models trained on these datasets is copied verbatim from the
training data. We develop two tools that allow us to deduplicate training
datasets -- for example removing from C4 a single 61 word English sentence that
is repeated over 60,000 times. Deduplication allows us to train models that
emit memorized text ten times less frequently and require fewer train steps to
achieve the same or better accuracy. We can also reduce train-test overlap,
which affects over 4% of the validation set of standard datasets, thus allowing
for more accurate evaluation. We release code for reproducing our work and
performing dataset deduplication at
https://github.com/google-research/deduplicate-text-datasets.