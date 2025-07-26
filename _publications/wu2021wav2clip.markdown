---
layout: publication
title: 'Wav2clip: Learning Robust Audio Representations From CLIP'
authors: Ho-hsiang Wu, Prem Seetharaman, Kundan Kumar, Juan Pablo Bello
conference: ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2022
bibkey: wu2021wav2clip
citations: 111
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.11499'}]
tags: ["Applications", "ICASSP", "Training Techniques"]
short_authors: Wu et al.
---
We propose Wav2CLIP, a robust audio representation learning method by
distilling from Contrastive Language-Image Pre-training (CLIP). We
systematically evaluate Wav2CLIP on a variety of audio tasks including
classification, retrieval, and generation, and show that Wav2CLIP can
outperform several publicly available pre-trained audio representation
algorithms. Wav2CLIP projects audio into a shared embedding space with images
and text, which enables multimodal applications such as zero-shot
classification, and cross-modal retrieval. Furthermore, Wav2CLIP needs just
~10% of the data to achieve competitive performance on downstream tasks
compared with fully supervised models, and is more efficient to pre-train than
competing methods as it does not require learning a visual model in concert
with an auditory model. Finally, we demonstrate image generation from Wav2CLIP
as qualitative assessment of the shared embedding space. Our code and model
weights are open sourced and made available for further applications.