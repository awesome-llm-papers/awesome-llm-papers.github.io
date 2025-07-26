---
layout: publication
title: 'Videoguide: Improving Video Diffusion Models Without Training Through A Teacher''s
  Guide'
authors: Dohun Lee, Bryan S Kim, Geon Yeong Park, Jong Chul Ye
conference: No Venue
year: 2024
bibkey: lee2024videoguide
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.04364'}]
tags: ["Has Code", "Tools"]
short_authors: Lee et al.
---
Text-to-image (T2I) diffusion models have revolutionized visual content creation, but extending these capabilities to text-to-video (T2V) generation remains a challenge, particularly in preserving temporal consistency. Existing methods that aim to improve consistency often cause trade-offs such as reduced imaging quality and impractical computational time. To address these issues we introduce VideoGuide, a novel framework that enhances the temporal consistency of pretrained T2V models without the need for additional training or fine-tuning. Instead, VideoGuide leverages any pretrained video diffusion model (VDM) or itself as a guide during the early stages of inference, improving temporal quality by interpolating the guiding model's denoised samples into the sampling model's denoising process. The proposed method brings about significant improvement in temporal consistency and image fidelity, providing a cost-effective and practical solution that synergizes the strengths of various video diffusion models. Furthermore, we demonstrate prior distillation, revealing that base models can achieve enhanced text coherence by utilizing the superior data prior of the guiding model through the proposed method. Project Page: http://videoguide2025.github.io/

https://huggingface.co/discussions/paper/6704b04906af66752cd6a359