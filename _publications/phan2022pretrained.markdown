---
layout: publication
title: 'Vit5: Pretrained Text-to-text Transformer For Vietnamese Language Generation'
authors: Long Phan, Hieu Tran, Hieu Nguyen, Trieu H. Trinh
conference: Arxiv
year: 2022
citations: 39
bibkey: phan2022pretrained
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.06457'}]
tags: [Language Modeling, Training Techniques, Transformer, Model Architecture]
---
We present ViT5, a pretrained Transformer-based encoder-decoder model for the
Vietnamese language. With T5-style self-supervised pretraining, ViT5 is trained
on a large corpus of high-quality and diverse Vietnamese texts. We benchmark
ViT5 on two downstream text generation tasks, Abstractive Text Summarization
and Named Entity Recognition. Although Abstractive Text Summarization has been
widely studied for the English language thanks to its rich and large source of
data, there has been minimal research into the same task in Vietnamese, a much
lower resource language. In this work, we perform exhaustive experiments on
both Vietnamese Abstractive Summarization and Named Entity Recognition,
validating the performance of ViT5 against many other pretrained
Transformer-based encoder-decoder models. Our experiments show that ViT5
significantly outperforms existing models and achieves state-of-the-art results
on Vietnamese Text Summarization. On the task of Named Entity Recognition, ViT5
is competitive against previous best results from pretrained encoder-based
Transformer models. Further analysis shows the importance of context length
during the self-supervised pretraining on downstream performance across
different settings.