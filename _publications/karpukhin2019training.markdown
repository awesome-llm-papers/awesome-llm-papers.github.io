---
layout: publication
title: Training On Synthetic Noise Improves Robustness To Natural Noise In Machine
  Translation
authors: Vladimir Karpukhin, Omer Levy, Jacob Eisenstein, Marjan Ghazvininejad
conference: Proceedings of the 5th Workshop on Noisy User-generated Text (W-NUT 2019)
year: 2019
bibkey: karpukhin2019training
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.01509'}]
tags: ["Training Techniques"]
short_authors: Karpukhin et al.
---
We consider the problem of making machine translation more robust to
character-level variation at the source side, such as typos. Existing methods
achieve greater coverage by applying subword models such as byte-pair encoding
(BPE) and character-level encoders, but these methods are highly sensitive to
spelling mistakes. We show how training on a mild amount of random synthetic
noise can dramatically improve robustness to these variations, without
diminishing performance on clean text. We focus on translation performance on
natural noise, as captured by frequent corrections in Wikipedia edit logs, and
show that robustness to such noise can be achieved using a balanced diet of
simple synthetic noises at training time, without access to the natural noise
data or distribution.