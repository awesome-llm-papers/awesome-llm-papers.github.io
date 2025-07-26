---
layout: publication
title: Contrastive Self-supervised Sequential Recommendation With Robust Augmentation
authors: Zhiwei Liu, Yongjun Chen, Jia Li, Philip S. Yu, Julian Mcauley, Caiming Xiong
conference: Arxiv
year: 2021
bibkey: liu2021contrastive
citations: 74
additional_links: [{name: Code, url: 'https://github.com/YChen1993/CoSeRec'}, {name: Paper,
    url: 'https://arxiv.org/abs/2108.06479'}]
tags: ["Training Techniques"]
short_authors: Liu et al.
---
Sequential Recommendationdescribes a set of techniques to model dynamic user
behavior in order to predict future interactions in sequential user data. At
their core, such approaches model transition probabilities between items in a
sequence, whether through Markov chains, recurrent networks, or more recently,
Transformers. However both old and new issues remain, including data-sparsity
and noisy data; such issues can impair the performance, especially in complex,
parameter-hungry models. In this paper, we investigate the application of
contrastive Self-Supervised Learning (SSL) to the sequential recommendation, as
a way to alleviate some of these issues. Contrastive SSL constructs
augmentations from unlabelled instances, where agreements among positive pairs
are maximized. It is challenging to devise a contrastive SSL framework for a
sequential recommendation, due to its discrete nature, correlations among
items, and skewness of length distributions. To this end, we propose a novel
framework, Contrastive Self-supervised Learning for sequential Recommendation
(CoSeRec). We introduce two informative augmentation operators leveraging item
correlations to create high-quality views for contrastive learning.
Experimental results on three real-world datasets demonstrate the effectiveness
of the proposed method on improving model performance and the robustness
against sparse and noisy data. Our implementation is available online at
https://github.com/YChen1993/CoSeRec