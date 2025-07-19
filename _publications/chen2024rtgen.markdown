---
layout: publication
title: 'Rtgen: Generating Region-text Pairs For Open-vocabulary Object Detection'
authors: Chen et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: chen2024rtgen
citations: 144
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.19854'}]
tags: [Prompting, Language Modeling, Training Techniques]
---
Open-vocabulary object detection (OVD) requires solid modeling of the
region-semantic relationship, which could be learned from massive region-text
pairs. However, such data is limited in practice due to significant annotation
costs. In this work, we propose RTGen to generate scalable open-vocabulary
region-text pairs and demonstrate its capability to boost the performance of
open-vocabulary object detection. RTGen includes both text-to-region and
region-to-text generation processes on scalable image-caption data. The
text-to-region generation is powered by image inpainting, directed by our
proposed scene-aware inpainting guider for overall layout harmony. For
region-to-text generation, we perform multiple region-level image captioning
with various prompts and select the best matching text according to CLIP
similarity. To facilitate detection training on region-text pairs, we also
introduce a localization-aware region-text contrastive loss that learns object
proposals tailored with different localization qualities. Extensive experiments
demonstrate that our RTGen can serve as a scalable, semantically rich, and
effective source for open-vocabulary object detection and continue to improve
the model performance when more data is utilized, delivering superior
performance compared to the existing state-of-the-art methods.