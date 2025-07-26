---
layout: publication
title: 'Lpcnet: Improving Neural Speech Synthesis Through Linear Prediction'
authors: Jean-marc Valin, Jan Skoglund
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: valin2018lpcnet
citations: 414
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.11846'}]
tags: ["Applications", "ICASSP"]
short_authors: Jean-marc Valin, Jan Skoglund
---
Neural speech synthesis models have recently demonstrated the ability to
synthesize high quality speech for text-to-speech and compression applications.
These new models often require powerful GPUs to achieve real-time operation, so
being able to reduce their complexity would open the way for many new
applications. We propose LPCNet, a WaveRNN variant that combines linear
prediction with recurrent neural networks to significantly improve the
efficiency of speech synthesis. We demonstrate that LPCNet can achieve
significantly higher quality than WaveRNN for the same network size and that
high quality LPCNet speech synthesis is achievable with a complexity under 3
GFLOPS. This makes it easier to deploy neural synthesis applications on
lower-power devices, such as embedded systems and mobile phones.