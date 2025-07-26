---
layout: publication
title: 'Hunyuancustom: A Multimodal-driven Architecture For Customized Video Generation'
authors: Teng Hu, Zhentao Yu, Zhengguang Zhou, Sen Liang, Yuan Zhou, Qin Lin, Qinglin
  Lu
conference: No Venue
year: 2025
bibkey: hu2025hunyuancustom
additional_links: [{name: Code, url: 'https://hunyuancustom.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/681c546e17fc8222efed54ce'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.04512'}]
tags: ["Model Architecture"]
short_authors: Hu et al.
---
Customized video generation aims to produce videos featuring specific subjects under flexible user-defined conditions, yet existing methods often struggle with identity consistency and limited input modalities. In this paper, we propose HunyuanCustom, a multi-modal customized video generation framework that emphasizes subject consistency while supporting image, audio, video, and text conditions. Built upon HunyuanVideo, our model first addresses the image-text conditioned generation task by introducing a text-image fusion module based on LLaVA for enhanced multi-modal understanding, along with an image ID enhancement module that leverages temporal concatenation to reinforce identity features across frames. To enable audio- and video-conditioned generation, we further propose modality-specific condition injection mechanisms: an AudioNet module that achieves hierarchical alignment via spatial cross-attention, and a video-driven injection module that integrates latent-compressed conditional video through a patchify-based feature-alignment network. Extensive experiments on single- and multi-subject scenarios demonstrate that HunyuanCustom significantly outperforms state-of-the-art open- and closed-source methods in terms of ID consistency, realism, and text-video alignment. Moreover, we validate its robustness across downstream tasks, including audio and video-driven customized video generation. Our results highlight the effectiveness of multi-modal conditioning and identity-preserving strategies in advancing controllable video generation. All the code and models are available at https://hunyuancustom.github.io.

https://huggingface.co/discussions/paper/681c546e17fc8222efed54ce