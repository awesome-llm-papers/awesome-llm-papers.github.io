---
layout: publication
title: 'Harnessing Indirect Training Data For End-to-end Automatic Speech Translation:
  Tricks Of The Trade'
authors: Pino et al.
conference: 2018 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2019
bibkey: pino2019harnessing
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.06515'}]
tags: [Training Techniques, Transformer, ICASSP, Model Architecture, Fine Tuning,
  Datasets]
---
For automatic speech translation (AST), end-to-end approaches are
outperformed by cascaded models that transcribe with automatic speech
recognition (ASR), then translate with machine translation (MT). A major cause
of the performance gap is that, while existing AST corpora are small, massive
datasets exist for both the ASR and MT subsystems. In this work, we evaluate
several data augmentation and pretraining approaches for AST, by comparing all
on the same datasets. Simple data augmentation by translating ASR transcripts
proves most effective on the English--French augmented LibriSpeech dataset,
closing the performance gap from 8.2 to 1.4 BLEU, compared to a very strong
cascade that could directly utilize copious ASR and MT data. The same
end-to-end approach plus fine-tuning closes the gap on the English--Romanian
MuST-C dataset from 6.7 to 3.7 BLEU. In addition to these results, we present
practical recommendations for augmentation and pretraining approaches. Finally,
we decrease the performance gap to 0.01 BLEU using a Transformer-based
architecture.