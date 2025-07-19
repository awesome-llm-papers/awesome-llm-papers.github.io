---
layout: publication
title: 'Mslam: Massively Multilingual Joint Pre-training For Speech And Text'
authors: Bapna et al.
conference: Arxiv
year: 2022
bibkey: bapna2022mslam
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.01374'}]
tags: [RAG, Training Techniques, BERT, Model Architecture, Reinforcement Learning,
  Fine Tuning, Multimodal Models]
---
We present mSLAM, a multilingual Speech and LAnguage Model that learns
cross-lingual cross-modal representations of speech and text by pre-training
jointly on large amounts of unlabeled speech and text in multiple languages.
mSLAM combines w2v-BERT pre-training on speech with SpanBERT pre-training on
character-level text, along with Connectionist Temporal Classification (CTC)
losses on paired speech and transcript data, to learn a single model capable of
learning from and representing both speech and text signals in a shared
representation space. We evaluate mSLAM on several downstream speech
understanding tasks and find that joint pre-training with text improves quality
on speech translation, speech intent classification and speech language-ID
while being competitive on multilingual ASR, when compared against speech-only
pre-training. Our speech translation model demonstrates zero-shot text
translation without seeing any text translation data, providing evidence for
cross-modal alignment of representations. mSLAM also benefits from multi-modal
fine-tuning, further improving the quality of speech translation by directly
leveraging text translation data during the fine-tuning process. Our empirical
analysis highlights several opportunities and challenges arising from
large-scale multimodal pre-training, suggesting directions for future research.