---
layout: publication
title: Natural TTS Synthesis By Conditioning Wavenet On Mel Spectrogram Predictions
authors: Shen et al.
conference: 2018 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2017
bibkey: shen2017natural
citations: 2338
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1712.05884'}]
tags: [ICASSP, Model Architecture]
---
This paper describes Tacotron 2, a neural network architecture for speech
synthesis directly from text. The system is composed of a recurrent
sequence-to-sequence feature prediction network that maps character embeddings
to mel-scale spectrograms, followed by a modified WaveNet model acting as a
vocoder to synthesize timedomain waveforms from those spectrograms. Our model
achieves a mean opinion score (MOS) of \\(4.53\\) comparable to a MOS of \\(4.58\\) for
professionally recorded speech. To validate our design choices, we present
ablation studies of key components of our system and evaluate the impact of
using mel spectrograms as the input to WaveNet instead of linguistic, duration,
and \\(F_0\\) features. We further demonstrate that using a compact acoustic
intermediate representation enables significant simplification of the WaveNet
architecture.