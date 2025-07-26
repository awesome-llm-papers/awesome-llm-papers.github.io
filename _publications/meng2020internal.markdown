---
layout: publication
title: Internal Language Model Estimation For Domain-adaptive End-to-end Speech Recognition
authors: Zhong Meng, Sarangarajan Parthasarathy, Eric Sun, Yashesh Gaur, Naoyuki Kanda,
  Liang Lu, Xie Chen, Rui Zhao, Jinyu Li, Yifan Gong
conference: 2021 IEEE Spoken Language Technology Workshop (SLT)
year: 2021
bibkey: meng2020internal
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.01991'}]
tags: ["Evaluation", "Model Architecture", "SLT", "Training Techniques"]
short_authors: Meng et al.
---
The external language models (LM) integration remains a challenging task for
end-to-end (E2E) automatic speech recognition (ASR) which has no clear division
between acoustic and language models. In this work, we propose an internal LM
estimation (ILME) method to facilitate a more effective integration of the
external LM with all pre-existing E2E models with no additional model training,
including the most popular recurrent neural network transducer (RNN-T) and
attention-based encoder-decoder (AED) models. Trained with audio-transcript
pairs, an E2E model implicitly learns an internal LM that characterizes the
training data in the source domain. With ILME, the internal LM scores of an E2E
model are estimated and subtracted from the log-linear interpolation between
the scores of the E2E model and the external LM. The internal LM scores are
approximated as the output of an E2E model when eliminating its acoustic
components. ILME can alleviate the domain mismatch between training and
testing, or improve the multi-domain E2E ASR. Experimented with 30K-hour
trained RNN-T and AED models, ILME achieves up to 15.5% and 6.8% relative word
error rate reductions from Shallow Fusion on out-of-domain LibriSpeech and
in-domain Microsoft production test sets, respectively.