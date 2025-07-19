---
layout: publication
title: 'Flashvideo: Flowing Fidelity To Detail For Efficient High-resolution Video
  Generation'
authors: Zhang et al.
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2025
bibkey: zhang2025flashvideo
citations: 406
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.05179'}]
tags: [RAG, ICCV, Prompting, Tools, Evaluation, Efficiency And Optimization, Merging]
---
DiT diffusion models have achieved great success in text-to-video generation,
leveraging their scalability in model capacity and data scale. High content and
motion fidelity aligned with text prompts, however, often require large model
parameters and a substantial number of function evaluations (NFEs). Realistic
and visually appealing details are typically reflected in high resolution
outputs, further amplifying computational demands especially for single stage
DiT models. To address these challenges, we propose a novel two stage
framework, FlashVideo, which strategically allocates model capacity and NFEs
across stages to balance generation fidelity and quality. In the first stage,
prompt fidelity is prioritized through a low resolution generation process
utilizing large parameters and sufficient NFEs to enhance computational
efficiency. The second stage establishes flow matching between low and high
resolutions, effectively generating fine details with minimal NFEs.
Quantitative and visual results demonstrate that FlashVideo achieves
state-of-the-art high resolution video generation with superior computational
efficiency. Additionally, the two-stage design enables users to preview the
initial output and accordingly adjust the prompt before committing to
full-resolution generation, thereby significantly reducing computational costs
and wait times as well as enhancing commercial viability.