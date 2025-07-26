---
layout: publication
title: Copy Is All You Need
authors: Tian Lan, Deng Cai, Yan Wang, Heyan Huang, Xian-ling Mao
conference: No Venue
year: 2023
bibkey: lan2023copy
additional_links: [{name: Code, url: 'https://github.com/gmftbyGMFTBY/Copyisallyouneed'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/64b48f5993679cd0095d8b6b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2307.06962'}]
tags: ["Efficiency", "Evaluation", "Fine-Tuning", "Has Code", "Training Techniques"]
short_authors: Lan et al.
---
The dominant text generation models compose the output by sequentially selecting words from a fixed vocabulary. In this paper, we formulate text generation as progressively copying text segments (e.g., words or phrases) from an existing text collection. We compute the contextualized representations of meaningful text segments and index them using efficient vector search toolkits. The task of text generation is then decomposed into a series of copy-and-paste operations: at each time step, we seek suitable text spans from the text collection rather than selecting from a standalone vocabulary. Experiments on the standard language modeling benchmark (WikiText-103) show that our approach achieves better generation quality according to both automatic and human evaluations. Besides, its inference efficiency is comparable to token-level autoregressive models thanks to the reduction of decoding steps. We also show that our approach allows for effective domain adaptation by simply switching to domain-specific text collection without extra training. Finally, we observe that our approach attains additional performance gains by simply scaling up to larger text collections, again without further training.Our source codes are publicly available at https://github.com/gmftbyGMFTBY/Copyisallyouneed.

https://huggingface.co/discussions/paper/64b48f5993679cd0095d8b6b