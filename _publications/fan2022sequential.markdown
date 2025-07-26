---
layout: publication
title: Sequential Recommendation With Auxiliary Item Relationships Via Multi-relational
  Transformer
authors: Ziwei Fan, Zhiwei Liu, Chen Wang, Peijie Huang, Hao Peng, Philip S. Yu
conference: Proceedings of the ACM Web Conference 2022
year: 2022
bibkey: fan2022sequential
citations: 119
additional_links: [{name: Code, url: 'https://github.com/zfan20/MT4SR'}, {name: Paper,
    url: 'https://arxiv.org/abs/2210.13572'}]
tags: ["Datasets", "Evaluation", "Has Code", "Model Architecture"]
short_authors: Fan et al.
---
Sequential Recommendation (SR) models user dynamics and predicts the next
preferred items based on the user history. Existing SR methods model the 'was
interacted before' item-item transitions observed in sequences, which can be
viewed as an item relationship. However, there are multiple auxiliary item
relationships, e.g., items from similar brands and with similar contents in
real-world scenarios. Auxiliary item relationships describe item-item
affinities in multiple different semantics and alleviate the long-lasting cold
start problem in the recommendation. However, it remains a significant
challenge to model auxiliary item relationships in SR.
  To simultaneously model high-order item-item transitions in sequences and
auxiliary item relationships, we propose a Multi-relational Transformer capable
of modeling auxiliary item relationships for SR (MT4SR). Specifically, we
propose a novel self-attention module, which incorporates arbitrary item
relationships and weights item relationships accordingly. Second, we regularize
intra-sequence item relationships with a novel regularization module to
supervise attentions computations. Third, for inter-sequence item relationship
pairs, we introduce a novel inter-sequence related items modeling module.
Finally, we conduct experiments on four benchmark datasets and demonstrate the
effectiveness of MT4SR over state-of-the-art methods and the improvements on
the cold start problem. The code is available at
https://github.com/zfan20/MT4SR.