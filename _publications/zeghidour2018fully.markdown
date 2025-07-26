---
layout: publication
title: Fully Convolutional Speech Recognition
authors: Neil Zeghidour, Qiantong Xu, Vitaliy Liptchinsky, Nicolas Usunier, Gabriel
  Synnaeve, Ronan Collobert
conference: Arxiv
year: 2018
bibkey: zeghidour2018fully
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1812.06864'}]
tags: ["Model Architecture"]
short_authors: Zeghidour et al.
---
Current state-of-the-art speech recognition systems build on recurrent neural
networks for acoustic and/or language modeling, and rely on feature extraction
pipelines to extract mel-filterbanks or cepstral coefficients. In this paper we
present an alternative approach based solely on convolutional neural networks,
leveraging recent advances in acoustic models from the raw waveform and
language modeling. This fully convolutional approach is trained end-to-end to
predict characters from the raw waveform, removing the feature extraction step
altogether. An external convolutional language model is used to decode words.
On Wall Street Journal, our model matches the current state-of-the-art. On
Librispeech, we report state-of-the-art performance among end-to-end models,
including Deep Speech 2 trained with 12 times more acoustic data and
significantly more linguistic data.