---
layout: publication
title: 'Realtoxicityprompts: Evaluating Neural Toxic Degeneration In Language Models'
authors: Samuel Gehman, Suchin Gururangan, Maarten Sap, Yejin Choi, Noah A. Smith
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: gehman2020realtoxicityprompts
citations: 430
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.11462'}]
tags: ["EMNLP"]
short_authors: Gehman et al.
---
Pretrained neural language models (LMs) are prone to generating racist,
sexist, or otherwise toxic language which hinders their safe deployment. We
investigate the extent to which pretrained LMs can be prompted to generate
toxic language, and the effectiveness of controllable text generation
algorithms at preventing such toxic degeneration. We create and release
RealToxicityPrompts, a dataset of 100K naturally occurring, sentence-level
prompts derived from a large corpus of English web text, paired with toxicity
scores from a widely-used toxicity classifier. Using RealToxicityPrompts, we
find that pretrained LMs can degenerate into toxic text even from seemingly
innocuous prompts. We empirically assess several controllable generation
methods, and find that while data- or compute-intensive methods (e.g., adaptive
pretraining on non-toxic data) are more effective at steering away from
toxicity than simpler solutions (e.g., banning "bad" words), no current method
is failsafe against neural toxic degeneration. To pinpoint the potential cause
of such persistent toxic degeneration, we analyze two web text corpora used to
pretrain several LMs (including GPT-2; Radford et. al, 2019), and find a
significant amount of offensive, factually unreliable, and otherwise toxic
content. Our work provides a test bed for evaluating toxic generations by LMs
and stresses the need for better data selection processes for pretraining.