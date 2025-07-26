---
layout: publication
title: Location-relative Attention Mechanisms For Robust Long-form Speech Synthesis
authors: Eric Battenberg, Rj Skerry-ryan, Soroosh Mariooryad, Daisy Stanton, David
  Kao, Matt Shannon, Tom Bagby
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: battenberg2019location
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.10288'}]
tags: ["ICASSP", "Model Architecture"]
short_authors: Battenberg et al.
---
Despite the ability to produce human-level speech for in-domain text,
attention-based end-to-end text-to-speech (TTS) systems suffer from text
alignment failures that increase in frequency for out-of-domain text. We show
that these failures can be addressed using simple location-relative attention
mechanisms that do away with content-based query/key comparisons. We compare
two families of attention mechanisms: location-relative GMM-based mechanisms
and additive energy-based mechanisms. We suggest simple modifications to
GMM-based attention that allow it to align quickly and consistently during
training, and introduce a new location-relative attention mechanism to the
additive energy-based family, called Dynamic Convolution Attention (DCA). We
compare the various mechanisms in terms of alignment speed and consistency
during training, naturalness, and ability to generalize to long utterances, and
conclude that GMM attention and DCA can generalize to very long utterances,
while preserving naturalness for shorter, in-domain utterances.