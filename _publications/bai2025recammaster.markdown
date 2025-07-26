---
layout: publication
title: 'Recammaster: Camera-controlled Generative Rendering From A Single Video'
authors: Jianhong Bai, Menghan Xia, Xiao Fu, Xintao Wang, Lianrui Mu, Jinwen Cao,
  Zuozhu Liu, Haoji Hu, Xiang Bai, Pengfei Wan, di Zhang
conference: No Venue
year: 2025
bibkey: bai2025recammaster
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.11647'}]
tags: ["Applications", "Has Code", "Tools"]
short_authors: Bai et al.
---
Camera control has been actively studied in text or image conditioned video generation tasks. However, altering camera trajectories of a given video remains under-explored, despite its importance in the field of video creation. It is non-trivial due to the extra constraints of maintaining multiple-frame appearance and dynamic synchronization. To address this, we present ReCamMaster, a camera-controlled generative video re-rendering framework that reproduces the dynamic scene of an input video at novel camera trajectories. The core innovation lies in harnessing the generative capabilities of pre-trained text-to-video models through a simple yet powerful video conditioning mechanism -- its capability often overlooked in current research. To overcome the scarcity of qualified training data, we construct a comprehensive multi-camera synchronized video dataset using Unreal Engine 5, which is carefully curated to follow real-world filming characteristics, covering diverse scenes and camera movements. It helps the model generalize to in-the-wild videos. Lastly, we further improve the robustness to diverse inputs through a meticulously designed training strategy. Extensive experiments tell that our method substantially outperforms existing state-of-the-art approaches and strong baselines. Our method also finds promising applications in video stabilization, super-resolution, and outpainting. Project page: https://jianhongbai.github.io/ReCamMaster/

https://huggingface.co/discussions/paper/67d785fb473d4edd330edf77