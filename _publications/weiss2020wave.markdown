---
layout: publication
title: 'Wave-tacotron: Spectrogram-free End-to-end Text-to-speech Synthesis'
authors: Ron J. Weiss, Rj Skerry-ryan, Eric Battenberg, Soroosh Mariooryad, Diederik
  P. Kingma
conference: ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2021
bibkey: weiss2020wave
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.03568'}]
tags: ["ICASSP", "Model Architecture"]
short_authors: Weiss et al.
---
We describe a sequence-to-sequence neural network which directly generates
speech waveforms from text inputs. The architecture extends the Tacotron model
by incorporating a normalizing flow into the autoregressive decoder loop.
Output waveforms are modeled as a sequence of non-overlapping fixed-length
blocks, each one containing hundreds of samples. The interdependencies of
waveform samples within each block are modeled using the normalizing flow,
enabling parallel training and synthesis. Longer-term dependencies are handled
autoregressively by conditioning each flow on preceding blocks.This model can
be optimized directly with maximum likelihood, with-out using intermediate,
hand-designed features nor additional loss terms. Contemporary state-of-the-art
text-to-speech (TTS) systems use a cascade of separately learned models: one
(such as Tacotron) which generates intermediate features (such as spectrograms)
from text, followed by a vocoder (such as WaveRNN) which generates waveform
samples from the intermediate features. The proposed system, in contrast, does
not use a fixed intermediate representation, and learns all parameters
end-to-end. Experiments show that the proposed model generates speech with
quality approaching a state-of-the-art neural TTS system, with significantly
improved generation speed.