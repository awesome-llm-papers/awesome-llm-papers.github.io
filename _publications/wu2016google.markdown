---
layout: publication
title: 'Google''s Neural Machine Translation System: Bridging The Gap Between Human
  And Machine Translation'
authors: "Yonghui Wu, Mike Schuster, Zhifeng Chen, Quoc V. Le, Mohammad Norouzi, Wolfgang\
  \ Macherey, Maxim Krikun, Yuan Cao, Qin Gao, Klaus Macherey, Jeff Klingner, Apurva\
  \ Shah, Melvin Johnson, Xiaobing Liu, \u0141ukasz Kaiser, Stephan Gouws, Yoshikiyo\
  \ Kato, Taku Kudo, Hideto Kazawa, Keith Stevens, George Kurian, Nishant Patil, Wei\
  \ Wang, Cliff Young, Jason Smith, Jason Riesa, Alex Rudnick, Oriol Vinyals, Greg\
  \ Corrado, Macduff Hughes, Jeffrey Dean"
conference: Arxiv
year: 2016
bibkey: wu2016google
citations: 5821
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.08144'}]
tags: ["Applications", "Efficiency", "Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Wu et al.
---
Neural Machine Translation (NMT) is an end-to-end learning approach for
automated translation, with the potential to overcome many of the weaknesses of
conventional phrase-based translation systems. Unfortunately, NMT systems are
known to be computationally expensive both in training and in translation
inference. Also, most NMT systems have difficulty with rare words. These issues
have hindered NMT's use in practical deployments and services, where both
accuracy and speed are essential. In this work, we present GNMT, Google's
Neural Machine Translation system, which attempts to address many of these
issues. Our model consists of a deep LSTM network with 8 encoder and 8 decoder
layers using attention and residual connections. To improve parallelism and
therefore decrease training time, our attention mechanism connects the bottom
layer of the decoder to the top layer of the encoder. To accelerate the final
translation speed, we employ low-precision arithmetic during inference
computations. To improve handling of rare words, we divide words into a limited
set of common sub-word units ("wordpieces") for both input and output. This
method provides a good balance between the flexibility of "character"-delimited
models and the efficiency of "word"-delimited models, naturally handles
translation of rare words, and ultimately improves the overall accuracy of the
system. Our beam search technique employs a length-normalization procedure and
uses a coverage penalty, which encourages generation of an output sentence that
is most likely to cover all the words in the source sentence. On the WMT'14
English-to-French and English-to-German benchmarks, GNMT achieves competitive
results to state-of-the-art. Using a human side-by-side evaluation on a set of
isolated simple sentences, it reduces translation errors by an average of 60%
compared to Google's phrase-based production system.