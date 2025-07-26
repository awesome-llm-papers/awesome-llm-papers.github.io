---
layout: publication
title: Investigation Of Enhanced Tacotron Text-to-speech Synthesis Systems With Self-attention
  For Pitch Accent Language
authors: Yusuke Yasuda, Xin Wang, Shinji Takaki, Junichi Yamagishi
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: yasuda2018investigation
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.11960'}]
tags: ["ICASSP", "Model Architecture", "Tools"]
short_authors: Yasuda et al.
---
End-to-end speech synthesis is a promising approach that directly converts
raw text to speech. Although it was shown that Tacotron2 outperforms classical
pipeline systems with regards to naturalness in English, its applicability to
other languages is still unknown. Japanese could be one of the most difficult
languages for which to achieve end-to-end speech synthesis, largely due to its
character diversity and pitch accents. Therefore, state-of-the-art systems are
still based on a traditional pipeline framework that requires a separate text
analyzer and duration model. Towards end-to-end Japanese speech synthesis, we
extend Tacotron to systems with self-attention to capture long-term
dependencies related to pitch accents and compare their audio quality with
classical pipeline systems under various conditions to show their pros and
cons. In a large-scale listening test, we investigated the impacts of the
presence of accentual-type labels, the use of force or predicted alignments,
and acoustic features used as local condition parameters of the Wavenet
vocoder. Our results reveal that although the proposed systems still do not
match the quality of a top-line pipeline system for Japanese, we show important
stepping stones towards end-to-end Japanese speech synthesis.