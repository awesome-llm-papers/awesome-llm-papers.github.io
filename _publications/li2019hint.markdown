---
layout: publication
title: Hint-based Training For Non-autoregressive Machine Translation
authors: Zhuohan Li, Zi Lin, di He, Fei Tian, Tao Qin, Liwei Wang, Tie-yan Liu
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: li2019hint
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.06708'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Li et al.
---
Due to the unparallelizable nature of the autoregressive factorization,
AutoRegressive Translation (ART) models have to generate tokens sequentially
during decoding and thus suffer from high inference latency. Non-AutoRegressive
Translation (NART) models were proposed to reduce the inference time, but could
only achieve inferior translation accuracy. In this paper, we proposed a novel
approach to leveraging the hints from hidden states and word alignments to help
the training of NART models. The results achieve significant improvement over
previous NART models for the WMT14 En-De and De-En datasets and are even
comparable to a strong LSTM-based ART baseline but one order of magnitude
faster in inference.