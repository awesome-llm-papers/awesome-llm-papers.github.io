---
layout: publication
title: 'ETC: Encoding Long And Structured Inputs In Transformers'
authors: Joshua Ainslie, Santiago Ontanon, Chris Alberti, Vaclav Cvicek, Zachary Fisher,
  Philip Pham, Anirudh Ravula, Sumit Sanghai, Qifan Wang, Li Yang
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: ainslie2020etc
citations: 246
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.08483'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Ainslie et al.
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