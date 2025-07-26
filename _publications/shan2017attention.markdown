---
layout: publication
title: Attention-based End-to-end Speech Recognition On Voice Search
authors: Changhao Shan, Junbo Zhang, Yujun Wang, Lei Xie
conference: 2018 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2018
bibkey: shan2017attention
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.07167'}]
tags: ["ICASSP", "Model Architecture"]
short_authors: Shan et al.
---
Recently, there has been a growing interest in end-to-end speech recognition
that directly transcribes speech to text without any predefined alignments. In
this paper, we explore the use of attention-based encoder-decoder model for
Mandarin speech recognition on a voice search task. Previous attempts have
shown that applying attention-based encoder-decoder to Mandarin speech
recognition was quite difficult due to the logographic orthography of Mandarin,
the large vocabulary and the conditional dependency of the attention model. In
this paper, we use character embedding to deal with the large vocabulary.
Several tricks are used for effective model training, including L2
regularization, Gaussian weight noise and frame skipping. We compare two
attention mechanisms and use attention smoothing to cover long context in the
attention model. Taken together, these tricks allow us to finally achieve a
character error rate (CER) of 3.58% and a sentence error rate (SER) of 7.43% on
the MiTV voice search dataset. While together with a trigram language model,
CER and SER reach 2.81% and 5.77%, respectively.