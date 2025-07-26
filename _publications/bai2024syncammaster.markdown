---
layout: publication
title: 'Syncammaster: Synchronizing Multi-camera Video Generation From Diverse Viewpoints'
authors: Jianhong Bai, Menghan Xia, Xintao Wang, Ziyang Yuan, Xiao Fu, Zuozhu Liu,
  Haoji Hu, Pengfei Wan, di Zhang
conference: No Venue
year: 2024
bibkey: bai2024syncammaster
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.07760'}]
tags: ["Applications", "Datasets", "Has Code", "Training Techniques"]
short_authors: Bai et al.
---
Recent advancements in video diffusion models have shown exceptional abilities in simulating real-world dynamics and maintaining 3D consistency. This progress inspires us to investigate the potential of these models to ensure dynamic consistency across various viewpoints, a highly desirable feature for applications such as virtual filming. Unlike existing methods focused on multi-view generation of single objects for 4D reconstruction, our interest lies in generating open-world videos from arbitrary viewpoints, incorporating 6 DoF camera poses. To achieve this, we propose a plug-and-play module that enhances a pre-trained text-to-video model for multi-camera video generation, ensuring consistent content across different viewpoints. Specifically, we introduce a multi-view synchronization module to maintain appearance and geometry consistency across these viewpoints. Given the scarcity of high-quality training data, we design a hybrid training scheme that leverages multi-camera images and monocular videos to supplement Unreal Engine-rendered multi-camera videos. Furthermore, our method enables intriguing extensions, such as re-rendering a video from novel viewpoints. We also release a multi-view synchronized video dataset, named SynCamVideo-Dataset. Project page: https://jianhongbai.github.io/SynCamMaster/.

https://huggingface.co/discussions/paper/67591887536995a5bc59a94c