---
layout: publication
title: 'Flowtron: An Autoregressive Flow-based Generative Network For Text-to-speech
  Synthesis'
authors: Rafael Valle, Kevin Shih, Ryan Prenger, Bryan Catanzaro
conference: Arxiv
year: 2020
bibkey: valle2020flowtron
citations: 79
additional_links: [{name: Code, url: 'https://github.com/NVIDIA/flowtron'}, {name: Paper,
    url: 'https://arxiv.org/abs/2005.05957'}]
tags: ["Training Techniques"]
short_authors: Valle et al.
---
In this paper we propose Flowtron: an autoregressive flow-based generative
network for text-to-speech synthesis with control over speech variation and
style transfer. Flowtron borrows insights from IAF and revamps Tacotron in
order to provide high-quality and expressive mel-spectrogram synthesis.
Flowtron is optimized by maximizing the likelihood of the training data, which
makes training simple and stable. Flowtron learns an invertible mapping of data
to a latent space that can be manipulated to control many aspects of speech
synthesis (pitch, tone, speech rate, cadence, accent). Our mean opinion scores
(MOS) show that Flowtron matches state-of-the-art TTS models in terms of speech
quality. In addition, we provide results on control of speech variation,
interpolation between samples and style transfer between speakers seen and
unseen during training. Code and pre-trained models will be made publicly
available at https://github.com/NVIDIA/flowtron