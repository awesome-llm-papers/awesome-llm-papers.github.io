---
layout: publication
title: 'Patch N'' Pack: Navit, A Vision Transformer For Any Aspect Ratio And Resolution'
authors: "Mostafa Dehghani, Basil Mustafa, Josip Djolonga, Jonathan Heek, Matthias\
  \ Minderer, Mathilde Caron, Andreas Steiner, Joan Puigcerver, Robert Geirhos, Ibrahim\
  \ Alabdulmohsin, Avital Oliver, Piotr Padlewski, Alexey Gritsenko, Mario Lu\u010D\
  i\u0107, Neil Houlsby"
conference: No Venue
year: 2023
bibkey: dehghani2023patch
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2307.06304'}]
tags: ["Model Architecture"]
short_authors: Dehghani et al.
---
The ubiquitous and demonstrably suboptimal choice of resizing images to a fixed resolution before processing them with computer vision models has not yet been successfully challenged. However, models such as the Vision Transformer (ViT) offer flexible sequence-based modeling, and hence varying input sequence lengths. We take advantage of this with NaViT (Native Resolution ViT) which uses sequence packing during training to process inputs of arbitrary resolutions and aspect ratios. Alongside flexible model usage, we demonstrate improved training efficiency for large-scale supervised and contrastive image-text pretraining. NaViT can be efficiently transferred to standard tasks such as image and video classification, object detection, and semantic segmentation and leads to improved results on robustness and fairness benchmarks. At inference time, the input resolution flexibility can be used to smoothly navigate the test-time cost-performance trade-off. We believe that NaViT marks a departure from the standard, CNN-designed, input and modelling pipeline used by most computer vision models, and represents a promising direction for ViTs.

https://huggingface.co/discussions/paper/64af7af4d2373ae50c0a3890