---
layout: publication
title: 'Reformer: The Efficient Transformer'
authors: "Nikita Kitaev, \u0141ukasz Kaiser, Anselm Levskaya"
conference: Arxiv
year: 2020
bibkey: kitaev2020reformer
citations: 897
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.04451'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: "Nikita Kitaev, \u0141ukasz Kaiser, Anselm Levskaya"
---
Large Transformer models routinely achieve state-of-the-art results on a
number of tasks but training these models can be prohibitively costly,
especially on long sequences. We introduce two techniques to improve the
efficiency of Transformers. For one, we replace dot-product attention by one
that uses locality-sensitive hashing, changing its complexity from O(\\(L^2\\)) to
O(\\(Llog L\\)), where \\(L\\) is the length of the sequence. Furthermore, we use
reversible residual layers instead of the standard residuals, which allows
storing activations only once in the training process instead of \\(N\\) times,
where \\(N\\) is the number of layers. The resulting model, the Reformer, performs
on par with Transformer models while being much more memory-efficient and much
faster on long sequences.