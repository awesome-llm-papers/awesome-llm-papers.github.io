---
layout: publication
title: Fine-grained Attention Mechanism For Neural Machine Translation
authors: Heeyoul Choi, Kyunghyun Cho, Yoshua Bengio
conference: Neurocomputing
year: 2018
bibkey: choi2018fine
citations: 196
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.11407'}]
tags: ["Model Architecture"]
short_authors: Heeyoul Choi, Kyunghyun Cho, Yoshua Bengio
---
Neural machine translation (NMT) has been a new paradigm in machine
translation, and the attention mechanism has become the dominant approach with
the state-of-the-art records in many language pairs. While there are variants
of the attention mechanism, all of them use only temporal attention where one
scalar value is assigned to one context vector corresponding to a source word.
In this paper, we propose a fine-grained (or 2D) attention mechanism where each
dimension of a context vector will receive a separate attention score. In
experiments with the task of En-De and En-Fi translation, the fine-grained
attention method improves the translation quality in terms of BLEU score. In
addition, our alignment analysis reveals how the fine-grained attention
mechanism exploits the internal structure of context vectors.