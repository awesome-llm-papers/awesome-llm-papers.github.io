---
layout: publication
title: 'Dialogxl: All-in-one Xlnet For Multi-party Conversation Emotion Recognition'
authors: Weizhou Shen, Junqing Chen, Xiaojun Quan, Zhixian Xie
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: shen2020dialogxl
citations: 177
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.08695'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Shen et al.
---
This paper presents our pioneering effort for emotion recognition in
conversation (ERC) with pre-trained language models. Unlike regular documents,
conversational utterances appear alternately from different parties and are
usually organized as hierarchical structures in previous work. Such structures
are not conducive to the application of pre-trained language models such as
XLNet. To address this issue, we propose an all-in-one XLNet model, namely
DialogXL, with enhanced memory to store longer historical context and
dialog-aware self-attention to deal with the multi-party structures.
Specifically, we first modify the recurrence mechanism of XLNet from
segment-level to utterance-level in order to better model the conversational
data. Second, we introduce dialog-aware self-attention in replacement of the
vanilla self-attention in XLNet to capture useful intra- and inter-speaker
dependencies. Extensive experiments are conducted on four ERC benchmarks with
mainstream models presented for comparison. The experimental results show that
the proposed model outperforms the baselines on all the datasets. Several other
experiments such as ablation study and error analysis are also conducted and
the results confirm the role of the critical modules of DialogXL.