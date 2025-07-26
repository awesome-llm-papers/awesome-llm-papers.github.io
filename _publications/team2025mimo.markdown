---
layout: publication
title: 'Mimo: Unlocking The Reasoning Potential Of Language Model -- From Pretraining
  To Posttraining'
authors: Xiaomi Llm-core Team, Bingquan Xia, Bowen Shen, Cici, Dawei Zhu, di Zhang,
  Gang Wang, Hailin Zhang, Huaqiu Liu, Jiebao Xiao, Jinhao Dong, Liang Zhao, Peidian
  Li, Peng Wang, Shihua Yu, Shimao Chen, Weikun Wang, Wenhan Ma, Xiangwei Deng, Yi
  Huang, Yifan Song, Zihan Jiang, Bowen Ye, Can Cai, Chenhong He, Dong Zhang, Duo
  Zhang, Guoan Wang, Hao Tian, Haochen Zhao, Heng Qu, Hongshen Xu, Jun Shi, Kainan
  Bao, Qingkai Fang, Kang Zhou, Kangyang Zhou, Lei Li, Menghang Zhu, Nuo Chen, Qiantong
  Wang, Shaohui Liu, Shicheng Li, Shuhao Gu, Shuhuai Ren, Shuo Liu, Sirui Deng, Weiji
  Zhuang, Weiwei Lv, Wenyu Yang, Xin Zhang, Xing Yong, Xing Zhang, Xingchen Song,
  Xinzhe Xu, Xu Wang, Yihan Yan, Yu Tu, Yuanyuan Tian, Yudong Wang, Yue Yu, Zhenru
  Lin, Zhichao Song, Zihao Yue
conference: No Venue
year: 2025
bibkey: team2025mimo
additional_links: [{name: Code, url: 'https://github.com/xiaomimimo/MiMo'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6822b5451f775dd12f7534e6'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.07608'}]
tags: ["Datasets", "Efficiency", "Has Code", "Reinforcement Learning", "Training Techniques"]
short_authors: Team et al.
---
We present MiMo-7B, a large language model born for reasoning tasks, with optimization across both pre-training and post-training stages. During pre-training, we enhance the data preprocessing pipeline and employ a three-stage data mixing strategy to strengthen the base model's reasoning potential. MiMo-7B-Base is pre-trained on 25 trillion tokens, with additional Multi-Token Prediction objective for enhanced performance and accelerated inference speed. During post-training, we curate a dataset of 130K verifiable mathematics and programming problems for reinforcement learning, integrating a test-difficulty-driven code-reward scheme to alleviate sparse-reward issues and employing strategic data resampling to stabilize training. Extensive evaluations show that MiMo-7B-Base possesses exceptional reasoning potential, outperforming even much larger 32B models. The final RL-tuned model, MiMo-7B-RL, achieves superior performance on mathematics, code and general reasoning tasks, surpassing the performance of OpenAI o1-mini. The model checkpoints are available at https://github.com/xiaomimimo/MiMo.

https://huggingface.co/discussions/paper/6822b5451f775dd12f7534e6