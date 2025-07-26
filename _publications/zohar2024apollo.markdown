---
layout: publication
title: 'Apollo: An Exploration Of Video Understanding In Large Multimodal Models'
authors: Orr Zohar, Xiaohan Wang, Yann Dubois, Nikhil Mehta, Tong Xiao, Philippe Hansen-estruch,
  Licheng Yu, Xiaofang Wang, Felix Juefei-xu, Ning Zhang, Serena Yeung-levy, Xide
  Xia
conference: No Venue
year: 2024
bibkey: zohar2024apollo
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/675f9d722eb87c3a1b120bb3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.10360'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Zohar et al.
---
Despite the rapid integration of video perception capabilities into Large Multimodal Models (LMMs), the underlying mechanisms driving their video understanding remain poorly understood. Consequently, many design decisions in this domain are made without proper justification or analysis. The high computational cost of training and evaluating such models, coupled with limited open research, hinders the development of video-LMMs. To address this, we present a comprehensive study that helps uncover what effectively drives video understanding in LMMs. We begin by critically examining the primary contributors to the high computational requirements associated with video-LMM research and discover Scaling Consistency, wherein design and training decisions made on smaller models and datasets (up to a critical size) effectively transfer to larger models. Leveraging these insights, we explored many video-specific aspects of video-LMMs, including video sampling, architectures, data composition, training schedules, and more. For example, we demonstrated that fps sampling during training is vastly preferable to uniform frame sampling and which vision encoders are the best for video representation. Guided by these findings, we introduce Apollo, a state-of-the-art family of LMMs that achieve superior performance across different model sizes. Our models can perceive hour-long videos efficiently, with Apollo-3B outperforming most existing 7B models with an impressive 55.1 on LongVideoBench. Apollo-7B is state-of-the-art compared to 7B LMMs with a 70.9 on MLVU, and 63.3 on Video-MME.

https://huggingface.co/discussions/paper/675f9d722eb87c3a1b120bb3