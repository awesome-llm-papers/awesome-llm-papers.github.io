---
layout: publication
title: A Skeleton-based Model For Promoting Coherence Among Sentences In Narrative
  Story Generation
authors: Jingjing Xu, Xuancheng Ren, Yi Zhang, Qi Zeng, Xiaoyan Cai, Xu Sun
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: xu2018skeleton
citations: 102
additional_links: [{name: Code, url: 'https://github.com/lancopku/Skeleton-Based-Generation-Model'},
  {name: Paper, url: 'https://arxiv.org/abs/1808.06945'}]
tags: ["EMNLP"]
short_authors: Xu et al.
---
Narrative story generation is a challenging problem because it demands the
generated sentences with tight semantic connections, which has not been well
studied by most existing generative models. To address this problem, we propose
a skeleton-based model to promote the coherence of generated stories. Different
from traditional models that generate a complete sentence at a stroke, the
proposed model first generates the most critical phrases, called skeleton, and
then expands the skeleton to a complete and fluent sentence. The skeleton is
not manually defined, but learned by a reinforcement learning method. Compared
to the state-of-the-art models, our skeleton-based model can generate
significantly more coherent text according to human evaluation and automatic
evaluation. The G-score is improved by 20.1% in the human evaluation. The code
is available at https://github.com/lancopku/Skeleton-Based-Generation-Model