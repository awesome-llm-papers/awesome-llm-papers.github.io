---
layout: publication
title: 'EVA-CLIP: Improved Training Techniques For CLIP At Scale'
authors: Quan Sun, Yuxin Fang, Ledell Wu, Xinlong Wang, Yue Cao
conference: Arxiv
year: 2023
bibkey: sun2023eva
citations: 63
additional_links: [{name: Code, url: 'https://github.com/baaivision/EVA/tree/master/EVA-CLIP'},
  {name: Paper, url: 'https://arxiv.org/abs/2303.15389'}]
tags: ["Training Techniques"]
short_authors: Sun et al.
---
Contrastive language-image pre-training, CLIP for short, has gained
increasing attention for its potential in various scenarios. In this paper, we
propose EVA-CLIP, a series of models that significantly improve the efficiency
and effectiveness of CLIP training. Our approach incorporates new techniques
for representation learning, optimization, and augmentation, enabling EVA-CLIP
to achieve superior performance compared to previous CLIP models with the same
number of parameters but significantly smaller training costs. Notably, our
largest 5.0B-parameter EVA-02-CLIP-E/14+ with only 9 billion seen samples
achieves 82.0 zero-shot top-1 accuracy on ImageNet-1K val. A smaller
EVA-02-CLIP-L/14+ with only 430 million parameters and 6 billion seen samples
achieves 80.4 zero-shot top-1 accuracy on ImageNet-1K val. To facilitate open
access and open research, we release the complete suite of EVA-CLIP to the
community at https://github.com/baaivision/EVA/tree/master/EVA-CLIP.