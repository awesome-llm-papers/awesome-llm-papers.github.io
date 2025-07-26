---
layout: publication
title: 'Funnel-transformer: Filtering Out Sequential Redundancy For Efficient Language
  Processing'
authors: Zihang Dai, Guokun Lai, Yiming Yang, Quoc V. Le
conference: Arxiv
year: 2020
bibkey: dai2020funnel
citations: 104
additional_links: [{name: Code, url: 'https://github.com/laiguokun/Funnel-Transformer'},
  {name: Paper, url: 'https://arxiv.org/abs/2006.03236'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Dai et al.
---
With the success of language pretraining, it is highly desirable to develop
more efficient architectures of good scalability that can exploit the abundant
unlabeled data at a lower cost. To improve the efficiency, we examine the
much-overlooked redundancy in maintaining a full-length token-level
presentation, especially for tasks that only require a single-vector
presentation of the sequence. With this intuition, we propose
Funnel-Transformer which gradually compresses the sequence of hidden states to
a shorter one and hence reduces the computation cost. More importantly, by
re-investing the saved FLOPs from length reduction in constructing a deeper or
wider model, we further improve the model capacity. In addition, to perform
token-level predictions as required by common pretraining objectives,
Funnel-Transformer is able to recover a deep representation for each token from
the reduced hidden sequence via a decoder. Empirically, with comparable or
fewer FLOPs, Funnel-Transformer outperforms the standard Transformer on a wide
variety of sequence-level prediction tasks, including text classification,
language understanding, and reading comprehension. The code and pretrained
checkpoints are available at https://github.com/laiguokun/Funnel-Transformer.