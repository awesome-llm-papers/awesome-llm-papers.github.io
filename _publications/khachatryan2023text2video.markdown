---
layout: publication
title: 'Text2video-zero: Text-to-image Diffusion Models Are Zero-shot Video Generators'
authors: Levon Khachatryan, Andranik Movsisyan, Vahram Tadevosyan, Roberto Henschel,
  Zhangyang Wang, Shant Navasardyan, Humphrey Shi
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: khachatryan2023text2video
citations: 165
additional_links: [{name: Code, url: 'https://github.com/Picsart-AI-Research/Text2Video-Zero'},
  {name: Paper, url: 'https://arxiv.org/abs/2303.13439'}]
tags: ["ICCV"]
short_authors: Khachatryan et al.
---
Recent text-to-video generation approaches rely on computationally heavy
training and require large-scale video datasets. In this paper, we introduce a
new task of zero-shot text-to-video generation and propose a low-cost approach
(without any training or optimization) by leveraging the power of existing
text-to-image synthesis methods (e.g., Stable Diffusion), making them suitable
for the video domain.
  Our key modifications include (i) enriching the latent codes of the generated
frames with motion dynamics to keep the global scene and the background time
consistent; and (ii) reprogramming frame-level self-attention using a new
cross-frame attention of each frame on the first frame, to preserve the
context, appearance, and identity of the foreground object.
  Experiments show that this leads to low overhead, yet high-quality and
remarkably consistent video generation. Moreover, our approach is not limited
to text-to-video synthesis but is also applicable to other tasks such as
conditional and content-specialized video generation, and Video
Instruct-Pix2Pix, i.e., instruction-guided video editing.
  As experiments show, our method performs comparably or sometimes better than
recent approaches, despite not being trained on additional video data. Our code
will be open sourced at: https://github.com/Picsart-AI-Research/Text2Video-Zero .