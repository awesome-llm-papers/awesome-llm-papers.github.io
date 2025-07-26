---
layout: publication
title: Scale-wise Distillation Of Diffusion Models
authors: Nikita Starodubcev, Denis Kuznedelev, Artem Babenko, Dmitry Baranchuk
conference: No Venue
year: 2025
bibkey: starodubcev2025scale
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.16397'}]
tags: ["Efficiency"]
short_authors: Starodubcev et al.
---
We present SwD, a scale-wise distillation framework for diffusion models (DMs), which effectively employs next-scale prediction ideas for diffusion-based few-step generators. In more detail, SwD is inspired by the recent insights relating diffusion processes to the implicit spectral autoregression. We suppose that DMs can initiate generation at lower data resolutions and gradually upscale the samples at each denoising step without loss in performance while significantly reducing computational costs. SwD naturally integrates this idea into existing diffusion distillation methods based on distribution matching. Also, we enrich the family of distribution matching approaches by introducing a novel patch loss enforcing finer-grained similarity to the target distribution. When applied to state-of-the-art text-to-image diffusion models, SwD approaches the inference times of two full resolution steps and significantly outperforms the counterparts under the same computation budget, as evidenced by automated metrics and human preference studies.

https://huggingface.co/discussions/paper/67dd1229046f2c38458e9617