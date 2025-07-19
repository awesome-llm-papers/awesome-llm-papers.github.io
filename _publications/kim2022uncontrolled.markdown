---
layout: publication
title: Uncontrolled Lexical Exposure Leads To Overestimation Of Compositional Generalization
  In Pretrained Models
authors: Kim Najoung, Linzen Tal, Smolensky Paul
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2022
bibkey: kim2022uncontrolled
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.10769'}]
tags: [Datasets, Training Techniques, Evaluation, EMNLP]
---
Human linguistic capacity is often characterized by compositionality and the
generalization it enables -- human learners can produce and comprehend novel
complex expressions by composing known parts. Several benchmarks exploit
distributional control across training and test to gauge compositional
generalization, where certain lexical items only occur in limited contexts
during training. While recent work using these benchmarks suggests that
pretrained models achieve impressive generalization performance, we argue that
exposure to pretraining data may break the aforementioned distributional
control. Using the COGS benchmark of Kim and Linzen (2020), we test two
modified evaluation setups that control for this issue: (1) substituting
context-controlled lexical items with novel character sequences, and (2)
substituting them with special tokens represented by novel embeddings. We find
that both of these setups lead to lower generalization performance in T5
(Raffel et al., 2020), suggesting that previously reported results have been
overestimated due to uncontrolled lexical exposure during pretraining. The
performance degradation is more extreme with novel embeddings, and the
degradation increases with the amount of pretraining data, highlighting an
interesting case of inverse scaling.