---
layout: publication
title: 'DAPO: An Open-source LLM Reinforcement Learning System At Scale'
authors: Qiying Yu, Zheng Zhang, Ruofei Zhu, Yufeng Yuan, Xiaochen Zuo, Yu Yue, Tiantian
  Fan, Gaohong Liu, Lingjun Liu, Xin Liu, Haibin Lin, Zhiqi Lin, Bole Ma, Guangming
  Sheng, Yuxuan Tong, Chi Zhang, Mofan Zhang, Wang Zhang, Hang Zhu, Jinhua Zhu, Jiaze
  Chen, Jiangjie Chen, Chengyi Wang, Hongli Yu, Weinan Dai, Yuxuan Song, Xiangpeng
  Wei, Hao Zhou, Jingjing Liu, Wei-ying Ma, Ya-qin Zhang, Lin Yan, Mu Qiao, Yonghui
  Wu, Mingxuan Wang
conference: No Venue
year: 2025
bibkey: yu2025dapo
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67da2b55e5335651349e26c7'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.14476'}]
tags: ["Reinforcement Learning", "Tools"]
short_authors: Yu et al.
---
Inference scaling empowers LLMs with unprecedented reasoning ability, with reinforcement learning as the core technique to elicit complex reasoning. However, key technical details of state-of-the-art reasoning LLMs are concealed (such as in OpenAI o1 blog and DeepSeek R1 technical report), thus the community still struggles to reproduce their RL training results. We propose the Decoupled Clip and Dynamic sAmpling Policy Optimization (DAPO) algorithm, and fully open-source a state-of-the-art large-scale RL system that achieves 50 points on AIME 2024 using Qwen2.5-32B base model. Unlike previous works that withhold training details, we introduce four key techniques of our algorithm that make large-scale LLM RL a success. In addition, we open-source our training code, which is built on the verl framework, along with a carefully curated and processed dataset. These components of our open-source system enhance reproducibility and support future research in large-scale LLM RL.

https://huggingface.co/discussions/paper/67da2b55e5335651349e26c7