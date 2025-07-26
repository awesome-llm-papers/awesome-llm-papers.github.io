---
layout: publication
title: Incorporating BERT Into Neural Machine Translation
authors: Jinhua Zhu, Yingce Xia, Lijun Wu, di He, Tao Qin, Wengang Zhou, Houqiang
  Li, Tie-yan Liu
conference: Arxiv
year: 2020
bibkey: zhu2020incorporating
citations: 223
additional_links: [{name: Code, url: 'https://github.com/bert-nmt/bert-nmt'}, {name: Paper,
    url: 'https://arxiv.org/abs/2002.06823'}]
tags: ["Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Zhu et al.
---
The recently proposed BERT has shown great power on a variety of natural
language understanding tasks, such as text classification, reading
comprehension, etc. However, how to effectively apply BERT to neural machine
translation (NMT) lacks enough exploration. While BERT is more commonly used as
fine-tuning instead of contextual embedding for downstream language
understanding tasks, in NMT, our preliminary exploration of using BERT as
contextual embedding is better than using for fine-tuning. This motivates us to
think how to better leverage BERT for NMT along this direction. We propose a
new algorithm named BERT-fused model, in which we first use BERT to extract
representations for an input sequence, and then the representations are fused
with each layer of the encoder and decoder of the NMT model through attention
mechanisms. We conduct experiments on supervised (including sentence-level and
document-level translations), semi-supervised and unsupervised machine
translation, and achieve state-of-the-art results on seven benchmark datasets.
Our code is available at https://github.com/bert-nmt/bert-nmt.