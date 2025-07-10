---
layout: publication
title: 'ETC: Encoding Long And Structured Inputs In Transformers'
authors: Joshua Ainslie et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
citations: 95
bibkey: ainslie2020encoding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.08483'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Pre-Training, Training
    Techniques]
---
Transformer models have advanced the state of the art in many Natural
Language Processing (NLP) tasks. In this paper, we present a new Transformer
architecture, Extended Transformer Construction (ETC), that addresses two key
challenges of standard Transformer architectures, namely scaling input length
and encoding structured inputs. To scale attention to longer inputs, we
introduce a novel global-local attention mechanism between global tokens and
regular input tokens. We also show that combining global-local attention with
relative position encodings and a Contrastive Predictive Coding (CPC)
pre-training objective allows ETC to encode structured inputs. We achieve
state-of-the-art results on four natural language datasets requiring long
and/or structured inputs.