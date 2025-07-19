---
layout: publication
title: 'Posetalk: Text-and-audio-based Pose Control And Motion Refinement For One-shot
  Talking Head Generation'
authors: Ling et al.
conference: Proceedings of the Thirtieth International Joint Conference on Artificial
  Intelligence
year: 2024
bibkey: ling2024posetalk
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.02657'}]
tags: [Merging, Prompting, Efficiency And Optimization, AAAI, IJCAI]
---
While previous audio-driven talking head generation (THG) methods generate
head poses from driving audio, the generated poses or lips cannot match the
audio well or are not editable. In this study, we propose \textbf\{PoseTalk\}, a
THG system that can freely generate lip-synchronized talking head videos with
free head poses conditioned on text prompts and audio. The core insight of our
method is using head pose to connect visual, linguistic, and audio signals.
First, we propose to generate poses from both audio and text prompts, where the
audio offers short-term variations and rhythm correspondence of the head
movements and the text prompts describe the long-term semantics of head
motions. To achieve this goal, we devise a Pose Latent Diffusion (PLD) model to
generate motion latent from text prompts and audio cues in a pose latent space.
Second, we observe a loss-imbalance problem: the loss for the lip region
contributes less than 4% of the total reconstruction loss caused by both pose
and lip, making optimization lean towards head movements rather than lip
shapes. To address this issue, we propose a refinement-based learning strategy
to synthesize natural talking videos using two cascaded networks, i.e.,
CoarseNet, and RefineNet. The CoarseNet estimates coarse motions to produce
animated images in novel poses and the RefineNet focuses on learning finer lip
motions by progressively estimating lip motions from low-to-high resolutions,
yielding improved lip-synchronization performance. Experiments demonstrate our
pose prediction strategy achieves better pose diversity and realness compared
to text-only or audio-only, and our video generator model outperforms
state-of-the-art methods in synthesizing talking videos with natural head
motions. Project: https://junleen.github.io/projects/posetalk.