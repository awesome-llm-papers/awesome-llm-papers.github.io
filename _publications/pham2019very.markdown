---
layout: publication
title: Very Deep Self-attention Networks For End-to-end Speech Recognition
authors: "Ngoc-quan Pham, Thai-son Nguyen, Jan Niehues, Markus M\xFCller, Sebastian\
  \ St\xFCker, Alexander Waibel"
conference: Interspeech 2019
year: 2019
bibkey: pham2019very
citations: 182
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.13377'}]
tags: ["INTERSPEECH", "Model Architecture"]
short_authors: Pham et al.
---
Recently, end-to-end sequence-to-sequence models for speech recognition have
gained significant interest in the research community. While previous
architecture choices revolve around time-delay neural networks (TDNN) and long
short-term memory (LSTM) recurrent neural networks, we propose to use
self-attention via the Transformer architecture as an alternative. Our analysis
shows that deep Transformer networks with high learning capacity are able to
exceed performance from previous end-to-end approaches and even match the
conventional hybrid systems. Moreover, we trained very deep models with up to
48 Transformer layers for both encoder and decoders combined with stochastic
residual connections, which greatly improve generalizability and training
efficiency. The resulting models outperform all previous end-to-end ASR
approaches on the Switchboard benchmark. An ensemble of these models achieve
9.9% and 17.7% WER on Switchboard and CallHome test sets respectively. This
finding brings our end-to-end models to competitive levels with previous hybrid
systems. Further, with model ensembling the Transformers can outperform certain
hybrid systems, which are more complicated in terms of both structure and
training procedure.