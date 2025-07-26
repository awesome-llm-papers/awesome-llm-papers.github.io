---
layout: publication
title: 'An Object Is Worth 64x64 Pixels: Generating 3D Object Via Image Diffusion'
authors: Xingguang Yan, Han-hung Lee, Ziyu Wan, Angel X. Chang
conference: No Venue
year: 2024
bibkey: yan2024object
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.03178'}]
tags: ["Datasets"]
short_authors: Yan et al.
---
We introduce a new approach for generating realistic 3D models with UV maps through a representation termed "Object Images." This approach encapsulates surface geometry, appearance, and patch structures within a 64x64 pixel image, effectively converting complex 3D shapes into a more manageable 2D format. By doing so, we address the challenges of both geometric and semantic irregularity inherent in polygonal meshes. This method allows us to use image generation models, such as Diffusion Transformers, directly for 3D shape generation. Evaluated on the ABO dataset, our generated shapes with patch structures achieve point cloud FID comparable to recent 3D generative models, while naturally supporting PBR material generation.

https://huggingface.co/discussions/paper/66b2dcd2fa7069c7f1f2302b