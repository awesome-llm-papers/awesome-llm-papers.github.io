---
layout: publication
title: 'FP8-LM: Training FP8 Large Language Models'
authors: Houwen Peng, Kan Wu, Yixuan Wei, Guoshuai Zhao, Yuxiang Yang, Ze Liu, Yifan
  Xiong, Ziyue Yang, Bolin Ni, Jingcheng Hu, Ruihang Li, Miaosen Zhang, Chen Li, Jia
  Ning, Ruizhe Wang, Zheng Zhang, Shuguang Liu, Joe Chau, Han Hu, Peng Cheng
conference: No Venue
year: 2023
bibkey: peng2023fp8
additional_links: [{name: Code, url: 'https://github.com/Azure/MS-AMP\}\{aka.ms/MS.AMP\'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2310.18313'}]
tags: ["Fine-Tuning", "Has Code", "Model Architecture", "Training Techniques"]
short_authors: Peng et al.
---
In this paper, we explore FP8 low-bit data formats for efficient training of large language models (LLMs). Our key insight is that most variables, such as gradients and optimizer states, in LLM training can employ low-precision data formats without compromising model accuracy and requiring no changes to hyper-parameters. Specifically, we propose a new FP8 automatic mixed-precision framework for training LLMs. This framework offers three levels of FP8 utilization to streamline mixed-precision and distributed parallel training for LLMs. It gradually incorporates 8-bit gradients, optimizer states, and distributed learning in an incremental manner. Experiment results show that, during the training of GPT-175B model on H100 GPU platform, our FP8 mixed-precision training framework not only achieved a remarkable 42% reduction in real memory usage but also ran 64% faster than the widely adopted BF16 framework (i.e., Megatron-LM), surpassing the speed of Nvidia Transformer Engine by 17%. This largely reduces the training costs for large foundation models. Furthermore, our FP8 mixed-precision training methodology is generic. It can be seamlessly applied to other tasks such as LLM instruction tuning and reinforcement learning with human feedback, offering savings in fine-tuning expenses. Our FP8 low-precision training framework is open-sourced at \{https://github.com/Azure/MS-AMP\}\{aka.ms/MS.AMP\}.

https://huggingface.co/discussions/paper/653f175be8ed050cb3513a4f