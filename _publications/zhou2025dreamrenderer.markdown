---
layout: publication
title: 'Dreamrenderer: Taming Multi-instance Attribute Control In Large-scale Text-to-image
  Models'
authors: Dewei Zhou, Mingwei Li, Zongxin Yang, Yi Yang
conference: No Venue
year: 2025
bibkey: zhou2025dreamrenderer
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.12885'}]
tags: ["Has Code", "Training Techniques"]
short_authors: Zhou et al.
---
Image-conditioned generation methods, such as depth- and canny-conditioned approaches, have demonstrated remarkable abilities for precise image synthesis. However, existing models still struggle to accurately control the content of multiple instances (or regions). Even state-of-the-art models like FLUX and 3DIS face challenges, such as attribute leakage between instances, which limits user control. To address these issues, we introduce DreamRenderer, a training-free approach built upon the FLUX model. DreamRenderer enables users to control the content of each instance via bounding boxes or masks, while ensuring overall visual harmony. We propose two key innovations: 1) Bridge Image Tokens for Hard Text Attribute Binding, which uses replicated image tokens as bridge tokens to ensure that T5 text embeddings, pre-trained solely on text data, bind the correct visual attributes for each instance during Joint Attention; 2) Hard Image Attribute Binding applied only to vital layers. Through our analysis of FLUX, we identify the critical layers responsible for instance attribute rendering and apply Hard Image Attribute Binding only in these layers, using soft binding in the others. This approach ensures precise control while preserving image quality. Evaluations on the COCO-POS and COCO-MIG benchmarks demonstrate that DreamRenderer improves the Image Success Ratio by 17.7% over FLUX and enhances the performance of layout-to-image models like GLIGEN and 3DIS by up to 26.8%. Project Page: https://limuloo.github.io/DreamRenderer/.

https://huggingface.co/discussions/paper/67d8e23cfa59a8b15a9058ba