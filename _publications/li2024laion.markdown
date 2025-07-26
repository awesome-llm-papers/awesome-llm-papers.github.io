---
layout: publication
title: 'LAION-SG: An Enhanced Large-scale Dataset For Training Complex Image-text
  Models With Structural Annotations'
authors: Zejian Li, Chenye Meng, Yize Li, Ling Yang, Shengyuan Zhang, Jiarui Ma, Jiayi
  Li, Guang Yang, Changyuan Yang, Zhiyuan Yang, Jinxiong Chang, Lingyun Sun
conference: No Venue
year: 2024
bibkey: li2024laion
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.08580'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Li et al.
---
Recent advances in text-to-image (T2I) generation have shown remarkable success in producing high-quality images from text. However, existing T2I models show decayed performance in compositional image generation involving multiple objects and intricate relationships. We attribute this problem to limitations in existing datasets of image-text pairs, which lack precise inter-object relationship annotations with prompts only. To address this problem, we construct LAION-SG, a large-scale dataset with high-quality structural annotations of scene graphs (SG), which precisely describe attributes and relationships of multiple objects, effectively representing the semantic structure in complex scenes. Based on LAION-SG, we train a new foundation model SDXL-SG to incorporate structural annotation information into the generation process. Extensive experiments show advanced models trained on our LAION-SG boast significant performance improvements in complex scene generation over models on existing datasets. We also introduce CompSG-Bench, a benchmark that evaluates models on compositional image generation, establishing a new standard for this domain.

https://huggingface.co/discussions/paper/675a609cca1f2b4cd6b2c12f