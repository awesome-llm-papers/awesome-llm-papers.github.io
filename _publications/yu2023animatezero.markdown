---
layout: publication
title: 'Animatezero: Video Diffusion Models Are Zero-shot Image Animators'
authors: Yu et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: yu2023animatezero
citations: 187
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.03793'}]
tags: [ICCV, Training Techniques, Attention Mechanism, Model Architecture, Applications,
  Merging]
---
Large-scale text-to-video (T2V) diffusion models have great progress in
recent years in terms of visual quality, motion and temporal consistency.
However, the generation process is still a black box, where all attributes
(e.g., appearance, motion) are learned and generated jointly without precise
control ability other than rough text descriptions. Inspired by image animation
which decouples the video as one specific appearance with the corresponding
motion, we propose AnimateZero to unveil the pre-trained text-to-video
diffusion model, i.e., AnimateDiff, and provide more precise appearance and
motion control abilities for it. For appearance control, we borrow intermediate
latents and their features from the text-to-image (T2I) generation for ensuring
the generated first frame is equal to the given generated image. For temporal
control, we replace the global temporal attention of the original T2V model
with our proposed positional-corrected window attention to ensure other frames
align with the first frame well. Empowered by the proposed methods, AnimateZero
can successfully control the generating progress without further training. As a
zero-shot image animator for given images, AnimateZero also enables multiple
new applications, including interactive video generation and real image
animation. The detailed experiments demonstrate the effectiveness of the
proposed method in both T2V and related applications.