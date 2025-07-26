---
layout: publication
title: 'FLOAT: Generative Motion Latent Flow Matching For Audio-driven Talking Portrait'
authors: Taekyung Ki, Dongchan Min, Gyoungsu Chae
conference: No Venue
year: 2024
bibkey: ki2024float
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.01064'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Taekyung Ki, Dongchan Min, Gyoungsu Chae
---
With the rapid advancement of diffusion-based generative models, portrait image animation has achieved remarkable results. However, it still faces challenges in temporally consistent video generation and fast sampling due to its iterative sampling nature. This paper presents FLOAT, an audio-driven talking portrait video generation method based on flow matching generative model. We shift the generative modeling from the pixel-based latent space to a learned motion latent space, enabling efficient design of temporally consistent motion. To achieve this, we introduce a transformer-based vector field predictor with a simple yet effective frame-wise conditioning mechanism. Additionally, our method supports speech-driven emotion enhancement, enabling a natural incorporation of expressive motions. Extensive experiments demonstrate that our method outperforms state-of-the-art audio-driven talking portrait methods in terms of visual quality, motion fidelity, and efficiency.

https://huggingface.co/discussions/paper/674e9ca8068c8178f4815ec9