---
layout: publication
title: A Survey On Non-autoregressive Generation For Neural Machine Translation And
  Beyond
authors: Xiao et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2022
bibkey: xiao2022survey
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.09269'}]
tags: [Model Architecture, Training Techniques, Survey Paper, Fine Tuning, Applications,
  LLM for Code, GPT, Attention Mechanism]
---
Non-autoregressive (NAR) generation, which is first proposed in neural
machine translation (NMT) to speed up inference, has attracted much attention
in both machine learning and natural language processing communities. While NAR
generation can significantly accelerate inference speed for machine
translation, the speedup comes at the cost of sacrificed translation accuracy
compared to its counterpart, autoregressive (AR) generation. In recent years,
many new models and algorithms have been designed/proposed to bridge the
accuracy gap between NAR generation and AR generation. In this paper, we
conduct a systematic survey with comparisons and discussions of various
non-autoregressive translation (NAT) models from different aspects.
Specifically, we categorize the efforts of NAT into several groups, including
data manipulation, modeling methods, training criterion, decoding algorithms,
and the benefit from pre-trained models. Furthermore, we briefly review other
applications of NAR models beyond machine translation, such as grammatical
error correction, text summarization, text style transfer, dialogue, semantic
parsing, automatic speech recognition, and so on. In addition, we also discuss
potential directions for future exploration, including releasing the dependency
of KD, reasonable training objectives, pre-training for NAR, and wider
applications, etc. We hope this survey can help researchers capture the latest
progress in NAR generation, inspire the design of advanced NAR models and
algorithms, and enable industry practitioners to choose appropriate solutions
for their applications. The web page of this survey is at
https://github.com/LitterBrother-Xiao/Overview-of-Non-autoregressive-Applications.