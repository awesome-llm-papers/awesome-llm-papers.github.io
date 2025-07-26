---
layout: publication
title: 'Clip4caption: CLIP For Video Caption'
authors: Mingkang Tang, Zhanyu Wang, Zhenhua Liu, Fengyun Rao, Dian Li, Xiu Li
conference: Proceedings of the 29th ACM International Conference on Multimedia
year: 2021
bibkey: tang2021clip4caption
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.06615'}]
tags: ["Tools"]
short_authors: Tang et al.
---
Video captioning is a challenging task since it requires generating sentences
describing various diverse and complex videos. Existing video captioning models
lack adequate visual representation due to the neglect of the existence of gaps
between videos and texts. To bridge this gap, in this paper, we propose a
CLIP4Caption framework that improves video captioning based on a CLIP-enhanced
video-text matching network (VTM). This framework is taking full advantage of
the information from both vision and language and enforcing the model to learn
strongly text-correlated video features for text generation. Besides, unlike
most existing models using LSTM or GRU as the sentence decoder, we adopt a
Transformer structured decoder network to effectively learn the long-range
visual and language dependency. Additionally, we introduce a novel ensemble
strategy for captioning tasks. Experimental results demonstrate the
effectiveness of our method on two datasets: 1) on MSR-VTT dataset, our method
achieved a new state-of-the-art result with a significant gain of up to 10% in
CIDEr; 2) on the private test data, our method ranking 2nd place in the ACM MM
multimedia grand challenge 2021: Pre-training for Video Understanding
Challenge. It is noted that our model is only trained on the MSR-VTT dataset.