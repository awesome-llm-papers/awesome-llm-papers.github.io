---
layout: publication
title: Context-aware Natural Language Generation With Recurrent Neural Networks
authors: Jian Tang, Yifan Yang, Sam Carton, Ming Zhang, Qiaozhu Mei
conference: Arxiv
year: 2016
bibkey: tang2016context
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.09900'}]
tags: ["Evaluation"]
short_authors: Tang et al.
---
This paper studied generating natural languages at particular contexts or
situations. We proposed two novel approaches which encode the contexts into a
continuous semantic representation and then decode the semantic representation
into text sequences with recurrent neural networks. During decoding, the
context information are attended through a gating mechanism, addressing the
problem of long-range dependency caused by lengthy sequences. We evaluate the
effectiveness of the proposed approaches on user review data, in which rich
contexts are available and two informative contexts, sentiments and products,
are selected for evaluation. Experiments show that the fake reviews generated
by our approaches are very natural. Results of fake review detection with human
judges show that more than 50% of the fake reviews are misclassified as the
real reviews, and more than 90% are misclassified by existing state-of-the-art
fake review detection algorithm.