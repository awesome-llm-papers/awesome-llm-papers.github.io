---
layout: publication
title: 'Sigma: Differential Rescaling Of Query, Key And Value For Efficient Language
  Models'
authors: Zhenghao Lin, Zihao Tang, Xiao Liu, Yeyun Gong, Yi Cheng, Qi Chen, Hang Li,
  Ying Xin, Ziyue Yang, Kailai Yang, Yu Yan, Xiao Liang, Shuai Lu, Yiming Huang, Zheheng
  Luo, Lei Qu, Xuan Feng, Yaoxiang Wang, Yuqing Xia, Feiyang Chen, Yuting Jiang, Yasen
  Hu, Hao Ni, Binyang Li, Guoshuai Zhao, Jui-hao Chiang, Zhongxin Guo, Chen Lin, Kun
  Kuang, Wenjie Li, Yelong Shen, Jian Jiao, Peng Cheng, Mao Yang
conference: No Venue
year: 2025
bibkey: lin2025sigma
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.13629'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Lin et al.
---
We introduce Sigma, an efficient large language model specialized for the system domain, empowered by a novel architecture including DiffQKV attention, and pre-trained on our meticulously collected system domain data. DiffQKV attention significantly enhances the inference efficiency of Sigma by optimizing the Query (Q), Key (K), and Value (V) components in the attention mechanism differentially, based on their varying impacts on the model performance and efficiency indicators. Specifically, we (1) conduct extensive experiments that demonstrate the model's varying sensitivity to the compression of K and V components, leading to the development of differentially compressed KV, and (2) propose augmented Q to expand the Q head dimension, which enhances the model's representation capacity with minimal impacts on the inference speed. Rigorous theoretical and empirical analyses reveal that DiffQKV attention significantly enhances efficiency, achieving up to a 33.36% improvement in inference speed over the conventional grouped-query attention (GQA) in long-context scenarios. We pre-train Sigma on 6T tokens from various sources, including 19.5B system domain data that we carefully collect and 1T tokens of synthesized and rewritten data. In general domains, Sigma achieves comparable performance to other state-of-arts models. In the system domain, we introduce the first comprehensive benchmark AIMicius, where Sigma demonstrates remarkable performance across all tasks, significantly outperforming GPT-4 with an absolute improvement up to 52.5%.

https://huggingface.co/discussions/paper/6792f8f05e3ec6035dafb140