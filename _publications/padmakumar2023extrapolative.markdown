---
layout: publication
title: Extrapolative Controlled Sequence Generation Via Iterative Refinement
authors: Padmakumar et al.
conference: Europhysics Letters (EPL)
year: 2023
bibkey: padmakumar2023extrapolative
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.04562'}]
tags: [Training Techniques]
---
We study the problem of extrapolative controlled generation, i.e., generating
sequences with attribute values beyond the range seen in training. This task is
of significant importance in automated design, especially drug discovery, where
the goal is to design novel proteins that are \textit\{better\} (e.g., more
stable) than existing sequences. Thus, by definition, the target sequences and
their attribute values are out of the training distribution, posing challenges
to existing methods that aim to directly generate the target sequence. Instead,
in this work, we propose Iterative Controlled Extrapolation (ICE) which
iteratively makes local edits to a sequence to enable extrapolation. We train
the model on synthetically generated sequence pairs that demonstrate small
improvement in the attribute value. Results on one natural language task
(sentiment analysis) and two protein engineering tasks (ACE2 stability and AAV
fitness) show that ICE considerably outperforms state-of-the-art approaches
despite its simplicity. Our code and models are available at:
https://github.com/vishakhpk/iter-extrapolation.