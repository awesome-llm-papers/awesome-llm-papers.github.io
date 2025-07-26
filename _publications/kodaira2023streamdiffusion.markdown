---
layout: publication
title: 'Streamdiffusion: A Pipeline-level Solution For Real-time Interactive Generation'
authors: Akio Kodaira, Chenfeng Xu, Toshiki Hazama, Takanori Yoshimoto, Kohei Ohno,
  Shogo Mitsuhori, Soichi Sugano, Hanying Cho, Zhijian Liu, Kurt Keutzer
conference: No Venue
year: 2023
bibkey: kodaira2023streamdiffusion
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2312.12491'}]
tags: ["Tools"]
short_authors: Kodaira et al.
---
We introduce StreamDiffusion, a real-time diffusion pipeline designed for interactive image generation. Existing diffusion models are adept at creating images from text or image prompts, yet they often fall short in real-time interaction. This limitation becomes particularly evident in scenarios involving continuous input, such as Metaverse, live video streaming, and broadcasting, where high throughput is imperative. To address this, we present a novel approach that transforms the original sequential denoising into the batching denoising process. Stream Batch eliminates the conventional wait-and-interact approach and enables fluid and high throughput streams. To handle the frequency disparity between data input and model throughput, we design a novel input-output queue for parallelizing the streaming process. Moreover, the existing diffusion pipeline uses classifier-free guidance(CFG), which requires additional U-Net computation. To mitigate the redundant computations, we propose a novel residual classifier-free guidance (RCFG) algorithm that reduces the number of negative conditional denoising steps to only one or even zero. Besides, we introduce a stochastic similarity filter(SSF) to optimize power consumption. Our Stream Batch achieves around 1.5x speedup compared to the sequential denoising method at different denoising levels. The proposed RCFG leads to speeds up to 2.05x higher than the conventional CFG. Combining the proposed strategies and existing mature acceleration tools makes the image-to-image generation achieve up-to 91.07fps on one RTX4090, improving the throughputs of AutoPipline developed by Diffusers over 59.56x. Furthermore, our proposed StreamDiffusion also significantly reduces the energy consumption by 2.39x on one RTX3060 and 1.99x on one RTX4090, respectively.

https://huggingface.co/discussions/paper/6583b6041fb17c3a9aad3e0c