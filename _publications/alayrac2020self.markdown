---
layout: publication
title: Self-supervised Multimodal Versatile Networks
authors: Alayrac et al.
conference: Arxiv
year: 2020
bibkey: alayrac2020self
citations: 178
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.16228'}]
tags: [RAG, Training Techniques, Evaluation, Multimodal Models, Datasets]
---
Videos are a rich source of multi-modal supervision. In this work, we learn
representations using self-supervision by leveraging three modalities naturally
present in videos: visual, audio and language streams. To this end, we
introduce the notion of a multimodal versatile network -- a network that can
ingest multiple modalities and whose representations enable downstream tasks in
multiple modalities. In particular, we explore how best to combine the
modalities, such that fine-grained representations of the visual and audio
modalities can be maintained, whilst also integrating text into a common
embedding. Driven by versatility, we also introduce a novel process of
deflation, so that the networks can be effortlessly applied to the visual data
in the form of video or a static image. We demonstrate how such networks
trained on large collections of unlabelled video data can be applied on video,
video-text, image and audio tasks. Equipped with these representations, we
obtain state-of-the-art performance on multiple challenging benchmarks
including UCF101, HMDB51, Kinetics600, AudioSet and ESC-50 when compared to
previous self-supervised work. Our models are publicly available.