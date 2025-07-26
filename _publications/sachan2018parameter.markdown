---
layout: publication
title: Parameter Sharing Methods For Multilingual Self-attentional Translation Models
authors: Devendra Singh Sachan, Graham Neubig
conference: 'Proceedings of the Third Conference on Machine Translation: Research
  Papers'
year: 2018
bibkey: sachan2018parameter
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.00252'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Devendra Singh Sachan, Graham Neubig
---
In multilingual neural machine translation, it has been shown that sharing a
single translation model between multiple languages can achieve competitive
performance, sometimes even leading to performance gains over bilingually
trained models. However, these improvements are not uniform; often multilingual
parameter sharing results in a decrease in accuracy due to translation models
not being able to accommodate different languages in their limited parameter
space. In this work, we examine parameter sharing techniques that strike a
happy medium between full sharing and individual training, specifically
focusing on the self-attentional Transformer model. We find that the full
parameter sharing approach leads to increases in BLEU scores mainly when the
target languages are from a similar language family. However, even in the case
where target languages are from different families where full parameter sharing
leads to a noticeable drop in BLEU scores, our proposed methods for partial
sharing of parameters can lead to substantial improvements in translation
accuracy.