---
layout: publication
title: 'Reality''s Canvas, Language''s Brush: Crafting 3D Avatars From Monocular Video'
authors: Rao et al.
conference: 2018 International Conference on 3D Vision (3DV)
year: 2023
bibkey: rao2023reality
citations: 157
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.04784'}]
tags: [Prompting, RAG, Merging]
---
Recent advancements in 3D avatar generation excel with multi-view supervision
for photorealistic models. However, monocular counterparts lag in quality
despite broader applicability. We propose ReCaLaB to close this gap. ReCaLaB is
a fully-differentiable pipeline that learns high-fidelity 3D human avatars from
just a single RGB video. A pose-conditioned deformable NeRF is optimized to
volumetrically represent a human subject in canonical T-pose. The canonical
representation is then leveraged to efficiently associate neural textures using
2D-3D correspondences. This enables the separation of diffused color generation
and lighting correction branches that jointly compose an RGB prediction. The
design allows to control intermediate results for human pose, body shape,
texture, and lighting with text prompts. An image-conditioned diffusion model
thereby helps to animate appearance and pose of the 3D avatar to create video
sequences with previously unseen human motion. Extensive experiments show that
ReCaLaB outperforms previous monocular approaches in terms of image quality for
image synthesis tasks. Moreover, natural language offers an intuitive user
interface for creative manipulation of 3D human avatars.