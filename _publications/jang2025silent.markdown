---
layout: publication
title: 'Silent Branding Attack: Trigger-free Data Poisoning Attack On Text-to-image
  Diffusion Models'
authors: Sangwon Jang, June Suk Choi, Jaehyeong Jo, Kimin Lee, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: jang2025silent
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.09669'}]
tags: ["Security"]
short_authors: Jang et al.
---
Text-to-image diffusion models have achieved remarkable success in generating high-quality contents from text prompts. However, their reliance on publicly available data and the growing trend of data sharing for fine-tuning make these models particularly vulnerable to data poisoning attacks. In this work, we introduce the Silent Branding Attack, a novel data poisoning method that manipulates text-to-image diffusion models to generate images containing specific brand logos or symbols without any text triggers. We find that when certain visual patterns are repeatedly in the training data, the model learns to reproduce them naturally in its outputs, even without prompt mentions. Leveraging this, we develop an automated data poisoning algorithm that unobtrusively injects logos into original images, ensuring they blend naturally and remain undetected. Models trained on this poisoned dataset generate images containing logos without degrading image quality or text alignment. We experimentally validate our silent branding attack across two realistic settings on large-scale high-quality image datasets and style personalization datasets, achieving high success rates even without a specific text trigger. Human evaluation and quantitative metrics including logo detection show that our method can stealthily embed logos.

https://huggingface.co/discussions/paper/67d37759e07f664c7325f3c5