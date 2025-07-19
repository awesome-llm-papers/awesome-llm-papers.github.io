---
layout: publication
title: Conditional LSTM-GAN For Melody Generation From Lyrics
authors: Yu Yi, Srivastava Abhishek, Canales Simon
conference: ACM Transactions on Multimedia Computing, Communications, and Applications
year: 2019
bibkey: yu2019conditional
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.05551'}]
tags: [RAG, Model Architecture, Security, Applications, Datasets]
---
Melody generation from lyrics has been a challenging research issue in the
field of artificial intelligence and music, which enables to learn and discover
latent relationship between interesting lyrics and accompanying melody.
Unfortunately, the limited availability of paired lyrics-melody dataset with
alignment information has hindered the research progress. To address this
problem, we create a large dataset consisting of 12,197 MIDI songs each with
paired lyrics and melody alignment through leveraging different music sources
where alignment relationship between syllables and music attributes is
extracted. Most importantly, we propose a novel deep generative model,
conditional Long Short-Term Memory - Generative Adversarial Network (LSTM-GAN)
for melody generation from lyrics, which contains a deep LSTM generator and a
deep LSTM discriminator both conditioned on lyrics. In particular,
lyrics-conditioned melody and alignment relationship between syllables of given
lyrics and notes of predicted melody are generated simultaneously. Experimental
results have proved the effectiveness of our proposed lyrics-to-melody
generative model, where plausible and tuneful sequences can be inferred from
lyrics.