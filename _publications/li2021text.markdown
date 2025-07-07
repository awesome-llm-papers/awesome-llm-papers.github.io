---
layout: publication
title: Text Compression-aided Transformer Encoding
authors: Zuchao Li et al.
conference: Arxiv
year: 2021
citations: 15
bibkey: li2021text
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.05951'}]
tags: [Attention Mechanism, Transformer, Model Architecture, Merging]
---
Text encoding is one of the most important steps in Natural Language
Processing (NLP). It has been done well by the self-attention mechanism in the
current state-of-the-art Transformer encoder, which has brought about
significant improvements in the performance of many NLP tasks. Though the
Transformer encoder may effectively capture general information in its
resulting representations, the backbone information, meaning the gist of the
input text, is not specifically focused on. In this paper, we propose explicit
and implicit text compression approaches to enhance the Transformer encoding
and evaluate models using this approach on several typical downstream tasks
that rely on the encoding heavily. Our explicit text compression approaches use
dedicated models to compress text, while our implicit text compression approach
simply adds an additional module to the main model to handle text compression.
We propose three ways of integration, namely backbone source-side fusion,
target-side fusion, and both-side fusion, to integrate the backbone information
into Transformer-based models for various downstream tasks. Our evaluation on
benchmark datasets shows that the proposed explicit and implicit text
compression approaches improve results in comparison to strong baselines. We
therefore conclude, when comparing the encodings to the baseline models, text
compression helps the encoders to learn better language representations.