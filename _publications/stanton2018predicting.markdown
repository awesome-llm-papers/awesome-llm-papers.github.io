---
layout: publication
title: Predicting Expressive Speaking Style From Text In End-to-end Speech Synthesis
authors: Daisy Stanton, Yuxuan Wang, Rj Skerry-ryan
conference: 2018 IEEE Spoken Language Technology Workshop (SLT)
year: 2018
bibkey: stanton2018predicting
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.01410'}]
tags: ["SLT"]
short_authors: Daisy Stanton, Yuxuan Wang, Rj Skerry-ryan
---
Global Style Tokens (GSTs) are a recently-proposed method to learn latent
disentangled representations of high-dimensional data. GSTs can be used within
Tacotron, a state-of-the-art end-to-end text-to-speech synthesis system, to
uncover expressive factors of variation in speaking style. In this work, we
introduce the Text-Predicted Global Style Token (TP-GST) architecture, which
treats GST combination weights or style embeddings as "virtual" speaking style
labels within Tacotron. TP-GST learns to predict stylistic renderings from text
alone, requiring neither explicit labels during training nor auxiliary inputs
for inference. We show that, when trained on a dataset of expressive speech,
our system generates audio with more pitch and energy variation than two
state-of-the-art baseline models. We further demonstrate that TP-GSTs can
synthesize speech with background noise removed, and corroborate these analyses
with positive results on human-rated listener preference audiobook tasks.
Finally, we demonstrate that multi-speaker TP-GST models successfully factorize
speaker identity and speaking style. We provide a website with audio samples
for each of our findings.