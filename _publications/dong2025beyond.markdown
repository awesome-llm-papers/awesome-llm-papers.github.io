---
layout: publication
title: 'Beyond CLIP Generalization: Against Forward&backward Forgetting Adapter For
  Continual Learning Of Vision-language Models'
authors: Dong et al.
conference: International Journal of Computer Vision
year: 2025
bibkey: dong2025beyond
citations: 395
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.07690'}]
tags: [Tools, Few Shot, Reinforcement Learning, Multimodal Models, Datasets]
---
This study aims to address the problem of multi-domain task incremental learning~(MTIL), which requires that vision-language models~(VLMs) continuously acquire new knowledge while maintaining their inherent zero-shot recognition capability. Existing paradigms delegate the testing of unseen-domain samples to the original CLIP, which only prevents the degradation of the model's zero-shot capability but fails to enhance the generalization of the VLM further. To this end, we propose a novel MTIL framework, named AFA, which comprises two core modules: (1) an against forward-forgetting adapter that learns task-invariant information for each dataset in the incremental tasks to enhance the zero-shot recognition ability of VLMs; (2) an against backward-forgetting adapter that strengthens the few-shot learning capability of VLMs while supporting incremental learning. Extensive experiments demonstrate that the AFA method significantly outperforms existing state-of-the-art approaches, especially in few-shot MTIL tasks, and surpasses the inherent zero-shot performance of CLIP in terms of transferability. The code is provided in the Supplementary Material.