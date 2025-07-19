---
layout: publication
title: Towards Neural Phrase-based Machine Translation
authors: Huang et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: huang2017towards
citations: 175
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.05565'}]
tags: [Model Architecture, SLT, EMNLP, Attention Mechanism]
---
In this paper, we present Neural Phrase-based Machine Translation (NPMT). Our
method explicitly models the phrase structures in output sequences using
Sleep-WAke Networks (SWAN), a recently proposed segmentation-based sequence
modeling method. To mitigate the monotonic alignment requirement of SWAN, we
introduce a new layer to perform (soft) local reordering of input sequences.
Different from existing neural machine translation (NMT) approaches, NPMT does
not use attention-based decoding mechanisms. Instead, it directly outputs
phrases in a sequential order and can decode in linear time. Our experiments
show that NPMT achieves superior performances on IWSLT 2014
German-English/English-German and IWSLT 2015 English-Vietnamese machine
translation tasks compared with strong NMT baselines. We also observe that our
method produces meaningful phrases in output languages.