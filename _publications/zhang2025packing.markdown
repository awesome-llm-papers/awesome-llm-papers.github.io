---
layout: publication
title: Packing Input Frame Context In Next-frame Prediction Models For Video Generation
authors: Lvmin Zhang, Maneesh Agrawala
conference: No Venue
year: 2025
bibkey: zhang2025packing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.12626'}]
tags: ["Memory & Context", "Model Architecture", "Training Techniques"]
short_authors: Lvmin Zhang, Maneesh Agrawala
---
We present a neural network structure, FramePack, to train next-frame (or next-frame-section) prediction models for video generation. The FramePack compresses input frames to make the transformer context length a fixed number regardless of the video length. As a result, we are able to process a large number of frames using video diffusion with computation bottleneck similar to image diffusion. This also makes the training video batch sizes significantly higher (batch sizes become comparable to image diffusion training). We also propose an anti-drifting sampling method that generates frames in inverted temporal order with early-established endpoints to avoid exposure bias (error accumulation over iterations). Finally, we show that existing video diffusion models can be finetuned with FramePack, and their visual quality may be improved because the next-frame prediction supports more balanced diffusion schedulers with less extreme flow shift timesteps.

https://huggingface.co/discussions/paper/6801b65281552de84a4b7e42