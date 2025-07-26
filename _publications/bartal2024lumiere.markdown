---
layout: publication
title: 'Lumiere: A Space-time Diffusion Model For Video Generation'
authors: Omer Bar-tal, Hila Chefer, Omer Tov, Charles Herrmann, Roni Paiss, Shiran
  Zada, Ariel Ephrat, Junhwa Hur, Yuanzhen Li, Tomer Michaeli, Oliver Wang, Deqing
  Sun, Tali Dekel, Inbar Mosseri
conference: No Venue
year: 2024
bibkey: bartal2024lumiere
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.12945'}]
tags: ["Applications", "Model Architecture"]
short_authors: Bar-tal et al.
---
We introduce Lumiere -- a text-to-video diffusion model designed for synthesizing videos that portray realistic, diverse and coherent motion -- a pivotal challenge in video synthesis. To this end, we introduce a Space-Time U-Net architecture that generates the entire temporal duration of the video at once, through a single pass in the model. This is in contrast to existing video models which synthesize distant keyframes followed by temporal super-resolution -- an approach that inherently makes global temporal consistency difficult to achieve. By deploying both spatial and (importantly) temporal down- and up-sampling and leveraging a pre-trained text-to-image diffusion model, our model learns to directly generate a full-frame-rate, low-resolution video by processing it in multiple space-time scales. We demonstrate state-of-the-art text-to-video generation results, and show that our design easily facilitates a wide range of content creation tasks and video editing applications, including image-to-video, video inpainting, and stylized generation.

https://huggingface.co/discussions/paper/65b06dcafdf08903343bffc7