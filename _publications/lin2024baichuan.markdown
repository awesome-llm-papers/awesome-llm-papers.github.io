---
layout: publication
title: Baichuan Alignment Technical Report
authors: Mingan Lin, Fan Yang, Yanjun Shen, Haoze Sun, Tianpeng Li, Tao Zhang, Chenzheng
  Zhu, Tao Zhang, Miao Zheng, Xu Li, Yijie Zhou, Mingyang Chen, Yanzhao Qin, Youquan
  Li, Hao Liang, Fei Li, Yadong Li, Mang Wang, Guosheng Dong, Kun Fang, Jianhua Xu,
  Bin Cui, Wentao Zhang, Zenan Zhou, Weipeng Chen
conference: No Venue
year: 2024
bibkey: lin2024baichuan
additional_links: [{name: Code, url: 'https://huggingface.co/PKU-Baichuan-MLSystemLab/Llama3-PBM-Nova-70B'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6717120a6914e88ea68a06b7'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.14940'}]
tags: ["Datasets", "Efficiency", "Evaluation", "Fine-Tuning", "Prompting"]
short_authors: Lin et al.
---
We introduce Baichuan Alignment, a detailed analysis of the alignment techniques employed in the Baichuan series of models. This represents the industry's first comprehensive account of alignment methodologies, offering valuable insights for advancing AI research. We investigate the critical components that enhance model performance during the alignment process, including optimization methods, data strategies, capability enhancements, and evaluation processes. The process spans three key stages: Prompt Augmentation System (PAS), Supervised Fine-Tuning (SFT), and Preference Alignment. The problems encountered, the solutions applied, and the improvements made are thoroughly recorded. Through comparisons across well-established benchmarks, we highlight the technological advancements enabled by Baichuan Alignment. Baichuan-Instruct is an internal model, while Qwen2-Nova-72B and Llama3-PBM-Nova-70B are instruct versions of the Qwen2-72B and Llama-3-70B base models, optimized through Baichuan Alignment. Baichuan-Instruct demonstrates significant improvements in core capabilities, with user experience gains ranging from 17% to 28%, and performs exceptionally well on specialized benchmarks. In open-source benchmark evaluations, both Qwen2-Nova-72B and Llama3-PBM-Nova-70B consistently outperform their respective official instruct versions across nearly all datasets. This report aims to clarify the key technologies behind the alignment process, fostering a deeper understanding within the community. Llama3-PBM-Nova-70B model is available at https://huggingface.co/PKU-Baichuan-MLSystemLab/Llama3-PBM-Nova-70B.

https://huggingface.co/discussions/paper/6717120a6914e88ea68a06b7