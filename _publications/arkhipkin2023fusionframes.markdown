---
layout: publication
title: 'Fusionframes: Efficient Architectural Aspects For Text-to-video Generation
  Pipeline'
authors: Vladimir Arkhipkin, Zein Shaheen, Viacheslav Vasilev, Elizaveta Dakhova,
  Andrey Kuznetsov, Denis Dimitrov
conference: No Venue
year: 2023
bibkey: arkhipkin2023fusionframes
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2311.13073'}]
tags: ["Model Architecture"]
short_authors: Arkhipkin et al.
---
Multimedia generation approaches occupy a prominent place in artificial intelligence research. Text-to-image models achieved high-quality results over the last few years. However, video synthesis methods recently started to develop. This paper presents a new two-stage latent diffusion text-to-video generation architecture based on the text-to-image diffusion model. The first stage concerns keyframes synthesis to figure the storyline of a video, while the second one is devoted to interpolation frames generation to make movements of the scene and objects smooth. We compare several temporal conditioning approaches for keyframes generation. The results show the advantage of using separate temporal blocks over temporal layers in terms of metrics reflecting video generation quality aspects and human preference. The design of our interpolation model significantly reduces computational costs compared to other masked frame interpolation approaches. Furthermore, we evaluate different configurations of MoVQ-based video decoding scheme to improve consistency and achieve higher PSNR, SSIM, MSE, and LPIPS scores. Finally, we compare our pipeline with existing solutions and achieve top-2 scores overall and top-1 among open-source solutions: CLIPSIM = 0.2976 and FVD = 433.054. Project page: https://ai-forever.github.io/kandinsky-video/

https://huggingface.co/discussions/paper/655eedc22ff001a46a51050a