---
layout: publication
title: Bidirectional Long-short Term Memory For Video Description
authors: Yi Bin, Yang Yang, Zi Huang, Fumin Shen, Xing Xu, Heng Tao Shen
conference: Proceedings of the 24th ACM international conference on Multimedia
year: 2016
bibkey: bin2016bidirectional
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.04631'}]
tags: ["Model Architecture"]
short_authors: Bin et al.
---
Video captioning has been attracting broad research attention in multimedia
community. However, most existing approaches either ignore temporal information
among video frames or just employ local contextual temporal knowledge. In this
work, we propose a novel video captioning framework, termed as
*Bidirectional Long-Short Term Memory* (BiLSTM), which deeply captures
bidirectional global temporal structure in video. Specifically, we first devise
a joint visual modelling approach to encode video data by combining a forward
LSTM pass, a backward LSTM pass, together with visual features from
Convolutional Neural Networks (CNNs). Then, we inject the derived video
representation into the subsequent language model for initialization. The
benefits are in two folds: 1) comprehensively preserving sequential and visual
information; and 2) adaptively learning dense visual features and sparse
semantic representations for videos and sentences, respectively. We verify the
effectiveness of our proposed video captioning framework on a commonly-used
benchmark, i.e., Microsoft Video Description (MSVD) corpus, and the
experimental results demonstrate that the superiority of the proposed approach
as compared to several state-of-the-art methods.