---
layout: publication
title: 'Magic-me: Identity-specific Video Customized Diffusion'
authors: Ze Ma, Daquan Zhou, Chun-hsiao Yeh, Xue-she Wang, Xiuyu Li, Huanrui Yang,
  Zhen Dong, Kurt Keutzer, Jiashi Feng
conference: No Venue
year: 2024
bibkey: ma2024magic
additional_links: [{name: Code, url: 'https://github.com/Zhen-Dong/Magic-Me'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/65cd79e53f97d5bd5d51c0e5'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2402.09368'}]
tags: ["Has Code", "Tools"]
short_authors: Ma et al.
---
Creating content for a specific identity (ID) has shown significant interest in the field of generative models. In the field of text-to-image generation (T2I), subject-driven content generation has achieved great progress with the ID in the images controllable. However, extending it to video generation is not well explored. In this work, we propose a simple yet effective subject identity controllable video generation framework, termed Video Custom Diffusion (VCD). With a specified subject ID defined by a few images, VCD reinforces the identity information extraction and injects frame-wise correlation at the initialization stage for stable video outputs with identity preserved to a large extent. To achieve this, we propose three novel components that are essential for high-quality ID preservation: 1) an ID module trained with the cropped identity by prompt-to-segmentation to disentangle the ID information and the background noise for more accurate ID token learning; 2) a text-to-video (T2V) VCD module with 3D Gaussian Noise Prior for better inter-frame consistency and 3) video-to-video (V2V) Face VCD and Tiled VCD modules to deblur the face and upscale the video for higher resolution. Despite its simplicity, we conducted extensive experiments to verify that VCD is able to generate stable and high-quality videos with better ID over the selected strong baselines. Besides, due to the transferability of the ID module, VCD is also working well with finetuned text-to-image models available publically, further improving its usability. The codes are available at https://github.com/Zhen-Dong/Magic-Me.

https://huggingface.co/discussions/paper/65cd79e53f97d5bd5d51c0e5