---
layout: publication
title: 'Depth Pro: Sharp Monocular Metric Depth In Less Than A Second'
authors: "Aleksei Bochkovskii, Ama\xEBl Delaunoy, Hugo Germain, Marcel Santos, Yichao\
  \ Zhou, Stephan R. Richter, Vladlen Koltun"
conference: No Venue
year: 2024
bibkey: bochkovskii2024depth
additional_links: [{name: Code, url: 'https://github.com/apple/ml-depth-pro'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66ff616181382f012c08a85d'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2410.02073'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Bochkovskii et al.
---
We present a foundation model for zero-shot metric monocular depth estimation. Our model, Depth Pro, synthesizes high-resolution depth maps with unparalleled sharpness and high-frequency details. The predictions are metric, with absolute scale, without relying on the availability of metadata such as camera intrinsics. And the model is fast, producing a 2.25-megapixel depth map in 0.3 seconds on a standard GPU. These characteristics are enabled by a number of technical contributions, including an efficient multi-scale vision transformer for dense prediction, a training protocol that combines real and synthetic datasets to achieve high metric accuracy alongside fine boundary tracing, dedicated evaluation metrics for boundary accuracy in estimated depth maps, and state-of-the-art focal length estimation from a single image. Extensive experiments analyze specific design choices and demonstrate that Depth Pro outperforms prior work along multiple dimensions. We release code and weights at https://github.com/apple/ml-depth-pro

https://huggingface.co/discussions/paper/66ff616181382f012c08a85d