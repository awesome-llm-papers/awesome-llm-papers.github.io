---
layout: publication
title: Style-friendly SNR Sampler For Style-driven Generation
authors: Jooyoung Choi, Chaehun Shin, Yeongtak Oh, Heeseung Kim, Sungroh Yoon
conference: No Venue
year: 2024
bibkey: choi2024style
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.14793'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Choi et al.
---
Recent large-scale diffusion models generate high-quality images but struggle to learn new, personalized artistic styles, which limits the creation of unique style templates. Fine-tuning with reference images is the most promising approach, but it often blindly utilizes objectives and noise level distributions used for pre-training, leading to suboptimal style alignment. We propose the Style-friendly SNR sampler, which aggressively shifts the signal-to-noise ratio (SNR) distribution toward higher noise levels during fine-tuning to focus on noise levels where stylistic features emerge. This enables models to better capture unique styles and generate images with higher style alignment. Our method allows diffusion models to learn and share new "style templates", enhancing personalized content creation. We demonstrate the ability to generate styles such as personal watercolor paintings, minimal flat cartoons, 3D renderings, multi-panel images, and memes with text, thereby broadening the scope of style-driven generation.

https://huggingface.co/discussions/paper/6743d88d5689f9445a5da4ec