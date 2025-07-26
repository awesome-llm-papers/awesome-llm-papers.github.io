---
layout: publication
title: 'Magictime: Time-lapse Video Generation Models As Metamorphic Simulators'
authors: Shenghai Yuan, Jinfa Huang, Yujun Shi, Yongqi Xu, Ruijie Zhu, Bin Lin, Xinhua
  Cheng, Li Yuan, Jiebo Luo
conference: No Venue
year: 2024
bibkey: yuan2024magictime
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6614b4f4c13e5d702f55d864'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.05014'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Yuan et al.
---
Recent advances in Text-to-Video generation (T2V) have achieved remarkable success in synthesizing high-quality general videos from textual descriptions. A largely overlooked problem in T2V is that existing models have not adequately encoded physical knowledge of the real world, thus generated videos tend to have limited motion and poor variations. In this paper, we propose MagicTime, a metamorphic time-lapse video generation model, which learns real-world physics knowledge from time-lapse videos and implements metamorphic generation. First, we design a MagicAdapter scheme to decouple spatial and temporal training, encode more physical knowledge from metamorphic videos, and transform pre-trained T2V models to generate metamorphic videos. Second, we introduce a Dynamic Frames Extraction strategy to adapt to metamorphic time-lapse videos, which have a wider variation range and cover dramatic object metamorphic processes, thus embodying more physical knowledge than general videos. Finally, we introduce a Magic Text-Encoder to improve the understanding of metamorphic video prompts. Furthermore, we create a time-lapse video-text dataset called ChronoMagic, specifically curated to unlock the metamorphic video generation ability. Extensive experiments demonstrate the superiority and effectiveness of MagicTime for generating high-quality and dynamic metamorphic videos, suggesting time-lapse video generation is a promising path toward building metamorphic simulators of the physical world.

https://huggingface.co/discussions/paper/6614b4f4c13e5d702f55d864