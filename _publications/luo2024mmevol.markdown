---
layout: publication
title: 'Mmevol: Empowering Multimodal Large Language Models With Evol-instruct'
authors: Run Luo, Haonan Zhang, Longze Chen, Ting-en Lin, Xiong Liu, Yuchuan Wu, Min
  Yang, Minzheng Wang, Pengpeng Zeng, Lianli Gao, Heng Tao Shen, Yunshui Li, Xiaobo
  Xia, Fei Huang, Jingkuan Song, Yongbin Li
conference: No Venue
year: 2024
bibkey: luo2024mmevol
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.05840'}]
tags: ["Model Architecture", "Tools"]
short_authors: Luo et al.
---
The development of Multimodal Large Language Models (MLLMs) has seen significant advancements. However, the quantity and quality of multimodal instruction data have emerged as significant bottlenecks in their progress. Manually creating multimodal instruction data is both time-consuming and inefficient, posing challenges in producing instructions of high complexity. Moreover, distilling instruction data from black-box commercial models (e.g., GPT-4o, GPT-4V) often results in simplistic instruction data, which constrains performance to that of these models. The challenge of curating diverse and complex instruction data remains substantial. We propose MMEvol, a novel multimodal instruction data evolution framework that combines fine-grained perception evolution, cognitive reasoning evolution, and interaction evolution. This iterative approach breaks through data quality bottlenecks to generate a complex and diverse image-text instruction dataset, thereby empowering MLLMs with enhanced capabilities. Beginning with an initial set of instructions, SEED-163K, we utilize MMEvol to systematically broadens the diversity of instruction types, integrates reasoning steps to enhance cognitive capabilities, and extracts detailed information from images to improve visual understanding and robustness. To comprehensively evaluate the effectiveness of our data, we train LLaVA-NeXT using the evolved data and conduct experiments across 13 vision-language tasks. Compared to the baseline trained with seed data, our approach achieves an average accuracy improvement of 3.1 points and reaches state-of-the-art (SOTA) performance on 9 of these tasks.

https://huggingface.co/discussions/paper/66dfa87256083f2760fa98f5