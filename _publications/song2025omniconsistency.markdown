---
layout: publication
title: 'Omniconsistency: Learning Style-agnostic Consistency From Paired Stylization
  Data'
authors: Yiren Song, Cheng Liu, Mike Zheng Shou
conference: No Venue
year: 2025
bibkey: song2025omniconsistency
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.18445'}]
tags: ["Model Architecture", "Tools"]
short_authors: Yiren Song, Cheng Liu, Mike Zheng Shou
---
Diffusion models have advanced image stylization significantly, yet two core challenges persist: (1) maintaining consistent stylization in complex scenes, particularly identity, composition, and fine details, and (2) preventing style degradation in image-to-image pipelines with style LoRAs. GPT-4o's exceptional stylization consistency highlights the performance gap between open-source methods and proprietary models. To bridge this gap, we propose OmniConsistency, a universal consistency plugin leveraging large-scale Diffusion Transformers (DiTs). OmniConsistency contributes: (1) an in-context consistency learning framework trained on aligned image pairs for robust generalization; (2) a two-stage progressive learning strategy decoupling style learning from consistency preservation to mitigate style degradation; and (3) a fully plug-and-play design compatible with arbitrary style LoRAs under the Flux framework. Extensive experiments show that OmniConsistency significantly enhances visual coherence and aesthetic quality, achieving performance comparable to commercial state-of-the-art model GPT-4o.

https://huggingface.co/discussions/paper/6835472bf57f43667ec53ae5