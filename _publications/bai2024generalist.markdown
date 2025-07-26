---
layout: publication
title: 'From Generalist To Specialist: Adapting Vision Language Models Via Task-specific
  Visual Instruction Tuning'
authors: Yang Bai, Yang Zhou, Jun Zhou, Rick Siow Mong Goh, Daniel Shu Wei Ting, Yong
  Liu
conference: No Venue
year: 2024
bibkey: bai2024generalist
additional_links: [{name: Code, url: 'https://github.com/baiyang4/VITask'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/670a14c102d531812e0467e2'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2410.06456'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Bai et al.
---
Large vision language models (VLMs) combine large language models with vision encoders, demonstrating promise across various tasks. However, they often underperform in task-specific applications due to domain gaps between pre-training and fine-tuning. We introduce VITask, a novel framework that enhances task-specific adaptability of VLMs by integrating task-specific models (TSMs). VITask employs three key strategies: exemplar prompting (EP), response distribution alignment (RDA), and contrastive response tuning (CRT) to improve the task-specific performance of VLMs by adjusting their response distributions. EP allows TSM features to guide VLMs, while RDA enables VLMs to adapt without TSMs during inference by learning from exemplar-prompted models. CRT further optimizes the ranking of correct image-response pairs, thereby reducing the risk of generating undesired responses. Experiments on 12 medical diagnosis datasets across 9 imaging modalities show that VITask outperforms both vanilla instruction-tuned VLMs and TSMs, showcasing its ability to integrate complementary features from both models effectively. Additionally, VITask offers practical advantages such as flexible TSM integration and robustness to incomplete instructions, making it a versatile and efficient solution for task-specific VLM tuning. Our code are available at https://github.com/baiyang4/VITask.

https://huggingface.co/discussions/paper/670a14c102d531812e0467e2