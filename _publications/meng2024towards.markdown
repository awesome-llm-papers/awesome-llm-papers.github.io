---
layout: publication
title: 'Towards World Simulator: Crafting Physical Commonsense-based Benchmark For
  Video Generation'
authors: Fanqing Meng, Jiaqi Liao, Xinyu Tan, Wenqi Shao, Quanfeng Lu, Kaipeng Zhang,
  Yu Cheng, Dianqi Li, Yu Qiao, Ping Luo
conference: No Venue
year: 2024
bibkey: meng2024towards
additional_links: [{name: Code, url: 'https://github.com/OpenGVLab/PhyGenBench'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67073024327cec6882e5d530'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.05363'}]
tags: ["Applications", "Evaluation", "Tools"]
short_authors: Meng et al.
---
Text-to-video (T2V) models like Sora have made significant strides in visualizing complex prompts, which is increasingly viewed as a promising path towards constructing the universal world simulator. Cognitive psychologists believe that the foundation for achieving this goal is the ability to understand intuitive physics. However, the capacity of these models to accurately represent intuitive physics remains largely unexplored. To bridge this gap, we introduce PhyGenBench, a comprehensive Physics Generation Benchmark designed to evaluate physical commonsense correctness in T2V generation. PhyGenBench comprises 160 carefully crafted prompts across 27 distinct physical laws, spanning four fundamental domains, which could comprehensively assesses models' understanding of physical commonsense. Alongside PhyGenBench, we propose a novel evaluation framework called PhyGenEval. This framework employs a hierarchical evaluation structure utilizing appropriate advanced vision-language models and large language models to assess physical commonsense. Through PhyGenBench and PhyGenEval, we can conduct large-scale automated assessments of T2V models' understanding of physical commonsense, which align closely with human feedback. Our evaluation results and in-depth analysis demonstrate that current models struggle to generate videos that comply with physical commonsense. Moreover, simply scaling up models or employing prompt engineering techniques is insufficient to fully address the challenges presented by PhyGenBench (e.g., dynamic scenarios). We hope this study will inspire the community to prioritize the learning of physical commonsense in these models beyond entertainment applications. We will release the data and codes at https://github.com/OpenGVLab/PhyGenBench

https://huggingface.co/discussions/paper/67073024327cec6882e5d530