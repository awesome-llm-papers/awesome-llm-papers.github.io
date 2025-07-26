---
layout: publication
title: 'Svdiff: Compact Parameter Space For Diffusion Fine-tuning'
authors: Ligong Han, Yinxiao Li, Han Zhang, Peyman Milanfar, Dimitris Metaxas, Feng
  Yang
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: han2023svdiff
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.11305'}]
tags: ["Fine-Tuning", "ICCV"]
short_authors: Han et al.
---
Diffusion models have achieved remarkable success in text-to-image
generation, enabling the creation of high-quality images from text prompts or
other modalities. However, existing methods for customizing these models are
limited by handling multiple personalized subjects and the risk of overfitting.
Moreover, their large number of parameters is inefficient for model storage. In
this paper, we propose a novel approach to address these limitations in
existing text-to-image diffusion models for personalization. Our method
involves fine-tuning the singular values of the weight matrices, leading to a
compact and efficient parameter space that reduces the risk of overfitting and
language drifting. We also propose a Cut-Mix-Unmix data-augmentation technique
to enhance the quality of multi-subject image generation and a simple
text-based image editing framework. Our proposed SVDiff method has a
significantly smaller model size compared to existing methods (approximately
2,200 times fewer parameters compared with vanilla DreamBooth), making it more
practical for real-world applications.