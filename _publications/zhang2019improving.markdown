---
layout: publication
title: Improving Deep Transformer With Depth-scaled Initialization And Merged Attention
authors: Zhang Biao, Titov Ivan, Sennrich Rico
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: zhang2019improving
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.11365'}]
tags: [RAG, EMNLP, Attention Mechanism, Transformer, Model Architecture, Efficiency
    And Optimization, SLT]
---
The general trend in NLP is towards increasing model capacity and performance
via deeper neural networks. However, simply stacking more layers of the popular
Transformer architecture for machine translation results in poor convergence
and high computational overhead. Our empirical analysis suggests that
convergence is poor due to gradient vanishing caused by the interaction between
residual connections and layer normalization. We propose depth-scaled
initialization (DS-Init), which decreases parameter variance at the
initialization stage, and reduces output variance of residual connections so as
to ease gradient back-propagation through normalization layers. To address
computational cost, we propose a merged attention sublayer (MAtt) which
combines a simplified averagebased self-attention sublayer and the
encoderdecoder attention sublayer on the decoder side. Results on WMT and IWSLT
translation tasks with five translation directions show that deep Transformers
with DS-Init and MAtt can substantially outperform their base counterpart in
terms of BLEU (+1.1 BLEU on average for 12-layer models), while matching the
decoding speed of the baseline model thanks to the efficiency improvements of
MAtt.