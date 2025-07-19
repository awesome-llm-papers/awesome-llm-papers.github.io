---
layout: publication
title: 'Repvideo: Rethinking Cross-layer Representation For Video Generation'
authors: Si et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: si2025repvideo
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.08994'}]
tags: [Training Techniques, Attention Mechanism, Tools, CVPR, Transformer, Model Architecture,
  Merging]
---
Video generation has achieved remarkable progress with the introduction of
diffusion models, which have significantly improved the quality of generated
videos. However, recent research has primarily focused on scaling up model
training, while offering limited insights into the direct impact of
representations on the video generation process. In this paper, we initially
investigate the characteristics of features in intermediate layers, finding
substantial variations in attention maps across different layers. These
variations lead to unstable semantic representations and contribute to
cumulative differences between features, which ultimately reduce the similarity
between adjacent frames and negatively affect temporal coherence. To address
this, we propose RepVideo, an enhanced representation framework for
text-to-video diffusion models. By accumulating features from neighboring
layers to form enriched representations, this approach captures more stable
semantic information. These enhanced representations are then used as inputs to
the attention mechanism, thereby improving semantic expressiveness while
ensuring feature consistency across adjacent frames. Extensive experiments
demonstrate that our RepVideo not only significantly enhances the ability to
generate accurate spatial appearances, such as capturing complex spatial
relationships between multiple objects, but also improves temporal consistency
in video generation.