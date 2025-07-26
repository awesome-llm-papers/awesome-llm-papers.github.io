---
layout: publication
title: Conditional Generation And Snapshot Learning In Neural Dialogue Systems
authors: Tsung-hsien Wen, Milica Gasic, Nikola Mrksic, Lina M. Rojas-barahona, Pei-hao
  Su, Stefan Ultes, David Vandyke, Steve Young
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: wen2016conditional
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.03352'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Wen et al.
---
Recently a variety of LSTM-based conditional language models (LM) have been
applied across a range of language generation tasks. In this work we study
various model architectures and different ways to represent and aggregate the
source information in an end-to-end neural dialogue system framework. A method
called snapshot learning is also proposed to facilitate learning from
supervised sequential signals by applying a companion cross-entropy objective
function to the conditioning vector. The experimental and analytical results
demonstrate firstly that competition occurs between the conditioning vector and
the LM, and the differing architectures provide different trade-offs between
the two. Secondly, the discriminative power and transparency of the
conditioning vector is key to providing both model interpretability and better
performance. Thirdly, snapshot learning leads to consistent performance
improvements independent of which architecture is used.