---
layout: publication
title: 'FELLE: Autoregressive Speech Synthesis With Token-wise Coarse-to-fine Flow
  Matching'
authors: Wang et al.
conference: IEEE Transactions on Systems, Man, and Cybernetics
year: 2025
bibkey: wang2025felle
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.11128'}]
tags: [Language Modeling, RAG, GPT, Ethics and Bias]
---
To advance continuous-valued token modeling and temporal-coherence
enforcement, we propose FELLE, an autoregressive model that integrates language
modeling with token-wise flow matching. By leveraging the autoregressive nature
of language models and the generative efficacy of flow matching, FELLE
effectively predicts continuous-valued tokens (mel-spectrograms). For each
continuous-valued token, FELLE modifies the general prior distribution in flow
matching by incorporating information from the previous step, improving
coherence and stability. Furthermore, to enhance synthesis quality, FELLE
introduces a coarse-to-fine flow-matching mechanism, generating
continuous-valued tokens hierarchically, conditioned on the language model's
output. Experimental results demonstrate the potential of incorporating
flow-matching techniques in autoregressive mel-spectrogram modeling, leading to
significant improvements in TTS generation quality, as shown in
https://aka.ms/felle.