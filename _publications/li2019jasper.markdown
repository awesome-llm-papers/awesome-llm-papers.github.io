---
layout: publication
title: 'Jasper: An End-to-end Convolutional Neural Acoustic Model'
authors: Jason Li, Vitaly Lavrukhin, Boris Ginsburg, Ryan Leary, Oleksii Kuchaiev,
  Jonathan M. Cohen, Huyen Nguyen, Ravi Teja Gadde
conference: Interspeech 2019
year: 2019
bibkey: li2019jasper
citations: 212
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.03288'}]
tags: ["INTERSPEECH", "Model Architecture"]
short_authors: Li et al.
---
In this paper, we report state-of-the-art results on LibriSpeech among
end-to-end speech recognition models without any external training data. Our
model, Jasper, uses only 1D convolutions, batch normalization, ReLU, dropout,
and residual connections. To improve training, we further introduce a new
layer-wise optimizer called NovoGrad. Through experiments, we demonstrate that
the proposed deep architecture performs as well or better than more complex
choices. Our deepest Jasper variant uses 54 convolutional layers. With this
architecture, we achieve 2.95% WER using a beam-search decoder with an external
neural language model and 3.86% WER with a greedy decoder on LibriSpeech
test-clean. We also report competitive results on the Wall Street Journal and
the Hub5'00 conversational evaluation datasets.