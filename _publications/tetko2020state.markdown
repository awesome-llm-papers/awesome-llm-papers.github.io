---
layout: publication
title: State-of-the-art Augmented NLP Transformer Models For Direct And Single-step
  Retrosynthesis
authors: Igor V. Tetko, Pavel Karpov, Ruud van Deursen, Guillaume Godin
conference: Nature Communications
year: 2020
bibkey: tetko2020state
citations: 332
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.02804'}]
tags: ["Model Architecture"]
short_authors: Tetko et al.
---
We investigated the effect of different training scenarios on predicting the
(retro)synthesis of chemical compounds using a text-like representation of
chemical reactions (SMILES) and Natural Language Processing neural network
Transformer architecture. We showed that data augmentation, which is a powerful
method used in image processing, eliminated the effect of data memorization by
neural networks, and improved their performance for the prediction of new
sequences. This effect was observed when augmentation was used simultaneously
for input and the target data simultaneously. The top-5 accuracy was 84.8% for
the prediction of the largest fragment (thus identifying principal
transformation for classical retro-synthesis) for the USPTO-50k test dataset
and was achieved by a combination of SMILES augmentation and a beam search
algorithm. The same approach provided significantly better results for the
prediction of direct reactions from the single-step USPTO-MIT test set. Our
model achieved 90.6% top-1 and 96.1% top-5 accuracy for its challenging mixed
set and 97% top-5 accuracy for the USPTO-MIT separated set. It also
significantly improved results for USPTO-full set single-step retrosynthesis
for both top-1 and top-10 accuracies. The appearance frequency of the most
abundantly generated SMILES was well correlated with the prediction outcome and
can be used as a measure of the quality of reaction prediction.