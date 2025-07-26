---
layout: publication
title: 'SAM 2: Segment Anything In Images And Videos'
authors: "Nikhila Ravi, Valentin Gabeur, Yuan-ting Hu, Ronghang Hu, Chaitanya Ryali,\
  \ Tengyu Ma, Haitham Khedr, Roman R\xE4dle, Chloe Rolland, Laura Gustafson, Eric\
  \ Mintun, Junting Pan, Kalyan Vasudev Alwala, Nicolas Carion, Chao-yuan Wu, Ross\
  \ Girshick, Piotr Doll\xE1r, Christoph Feichtenhofer"
conference: No Venue
year: 2024
bibkey: ravi2024sam
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.00714'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Ravi et al.
---
We present Segment Anything Model 2 (SAM 2), a foundation model towards solving promptable visual segmentation in images and videos. We build a data engine, which improves model and data via user interaction, to collect the largest video segmentation dataset to date. Our model is a simple transformer architecture with streaming memory for real-time video processing. SAM 2 trained on our data provides strong performance across a wide range of tasks. In video segmentation, we observe better accuracy, using 3x fewer interactions than prior approaches. In image segmentation, our model is more accurate and 6x faster than the Segment Anything Model (SAM). We believe that our data, model, and insights will serve as a significant milestone for video segmentation and related perception tasks. We are releasing a version of our model, the dataset and an interactive demo.

https://huggingface.co/discussions/paper/66ac44677746f1e5ff6b71f3