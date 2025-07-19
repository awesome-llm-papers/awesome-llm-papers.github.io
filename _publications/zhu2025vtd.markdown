---
layout: publication
title: 'VTD-CLIP: Video-to-text Discretization Via Prompting CLIP'
authors: Zhu et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: zhu2025vtd
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.18407'}]
tags: [Interpretability And Explainability, Training Techniques, Prompting, Tools,
  CVPR, Time Series, Security, Fine Tuning, Multimodal Models, Merging]
---
Vision-language models bridge visual and linguistic understanding and have
proven to be powerful for video recognition tasks. Existing approaches
primarily rely on parameter-efficient fine-tuning of image-text pre-trained
models, yet they often suffer from limited interpretability and poor
generalization due to inadequate temporal modeling. To address these, we
propose a simple yet effective video-to-text discretization framework. Our
method repurposes the frozen text encoder to construct a visual codebook from
video class labels due to the many-to-one contrastive alignment between visual
and textual embeddings in multimodal pretraining. This codebook effectively
transforms temporal visual data into textual tokens via feature lookups and
offers interpretable video representations through explicit video modeling.
Then, to enhance robustness against irrelevant or noisy frames, we introduce a
confidence-aware fusion module that dynamically weights keyframes by assessing
their semantic relevance via the codebook. Furthermore, our method incorporates
learnable text prompts to conduct adaptive codebook updates. Extensive
experiments on HMDB-51, UCF-101, SSv2, and Kinetics-400 have validated the
superiority of our approach, achieving more competitive improvements over
state-of-the-art methods. The code will be publicly available at
https://github.com/isxinxin/VTD-CLIP.