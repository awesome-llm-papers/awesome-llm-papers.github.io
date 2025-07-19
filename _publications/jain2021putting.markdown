---
layout: publication
title: 'Putting Nerf On A Diet: Semantically Consistent Few-shot View Synthesis'
authors: Jain Ajay, Tancik Matthew, Abbeel Pieter
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: jain2021putting
citations: 292
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.00677'}]
tags: [RAG, ICCV, Transformer, Model Architecture, Few Shot, Datasets]
---
We present DietNeRF, a 3D neural scene representation estimated from a few
images. Neural Radiance Fields (NeRF) learn a continuous volumetric
representation of a scene through multi-view consistency, and can be rendered
from novel viewpoints by ray casting. While NeRF has an impressive ability to
reconstruct geometry and fine details given many images, up to 100 for
challenging 360\{\deg\} scenes, it often finds a degenerate solution to its image
reconstruction objective when only a few input views are available. To improve
few-shot quality, we propose DietNeRF. We introduce an auxiliary semantic
consistency loss that encourages realistic renderings at novel poses. DietNeRF
is trained on individual scenes to (1) correctly render given input views from
the same pose, and (2) match high-level semantic attributes across different,
random poses. Our semantic loss allows us to supervise DietNeRF from arbitrary
poses. We extract these semantics using a pre-trained visual encoder such as
CLIP, a Vision Transformer trained on hundreds of millions of diverse
single-view, 2D photographs mined from the web with natural language
supervision. In experiments, DietNeRF improves the perceptual quality of
few-shot view synthesis when learned from scratch, can render novel views with
as few as one observed image when pre-trained on a multi-view dataset, and
produces plausible completions of completely unobserved regions.