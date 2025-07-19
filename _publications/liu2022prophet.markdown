---
layout: publication
title: 'Prophet Attention: Predicting Attention With Future Attention For Image Captioning'
authors: Liu et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2022
bibkey: liu2022prophet
citations: 712
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.10914'}]
tags: [ICCV, Training Techniques, Attention Mechanism, Evaluation, Model Architecture,
  Datasets]
---
Recently, attention based models have been used extensively in many
sequence-to-sequence learning systems. Especially for image captioning, the
attention based models are expected to ground correct image regions with proper
generated words. However, for each time step in the decoding process, the
attention based models usually use the hidden state of the current input to
attend to the image regions. Under this setting, these attention models have a
"deviated focus" problem that they calculate the attention weights based on
previous words instead of the one to be generated, impairing the performance of
both grounding and captioning. In this paper, we propose the Prophet Attention,
similar to the form of self-supervision. In the training stage, this module
utilizes the future information to calculate the "ideal" attention weights
towards image regions. These calculated "ideal" weights are further used to
regularize the "deviated" attention. In this manner, image regions are grounded
with the correct words. The proposed Prophet Attention can be easily
incorporated into existing image captioning models to improve their performance
of both grounding and captioning. The experiments on the Flickr30k Entities and
the MSCOCO datasets show that the proposed Prophet Attention consistently
outperforms baselines in both automatic metrics and human evaluations. It is
worth noticing that we set new state-of-the-arts on the two benchmark datasets
and achieve the 1st place on the leaderboard of the online MSCOCO benchmark in
terms of the default ranking score, i.e., CIDEr-c40.