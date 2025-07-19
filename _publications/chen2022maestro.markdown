---
layout: publication
title: 'MAESTRO: Matched Speech Text Representations Through Modality Matching'
authors: Chen et al.
conference: Interspeech 2022
year: 2022
bibkey: chen2022maestro
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.03409'}]
tags: [RAG, INTERSPEECH, Training Techniques]
---
We present Maestro, a self-supervised training method to unify
representations learnt from speech and text modalities. Self-supervised
learning from speech signals aims to learn the latent structure inherent in the
signal, while self-supervised learning from text attempts to capture lexical
information. Learning aligned representations from unpaired speech and text
sequences is a challenging task. Previous work either implicitly enforced the
representations learnt from these two modalities to be aligned in the latent
space through multitasking and parameter sharing or explicitly through
conversion of modalities via speech synthesis. While the former suffers from
interference between the two modalities, the latter introduces additional
complexity. In this paper, we propose Maestro, a novel algorithm to learn
unified representations from both these modalities simultaneously that can
transfer to diverse downstream tasks such as Automated Speech Recognition (ASR)
and Speech Translation (ST). Maestro learns unified representations through
sequence alignment, duration prediction and matching embeddings in the learned
space through an aligned masked-language model loss. We establish a new
state-of-the-art (SOTA) on VoxPopuli multilingual ASR with a 8% relative
reduction in Word Error Rate (WER), multidomain SpeechStew ASR (3.7% relative)
and 21 languages to English multilingual ST on CoVoST 2 with an improvement of
2.8 BLEU averaged over 21 languages.