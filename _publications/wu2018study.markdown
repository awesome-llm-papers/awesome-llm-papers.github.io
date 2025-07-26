---
layout: publication
title: A Study Of Reinforcement Learning For Neural Machine Translation
authors: Lijun Wu, Fei Tian, Tao Qin, Jianhuang Lai, Tie-yan Liu
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: wu2018study
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.08866'}]
tags: ["EMNLP", "Reinforcement Learning"]
short_authors: Wu et al.
---
Recent studies have shown that reinforcement learning (RL) is an effective
approach for improving the performance of neural machine translation (NMT)
system. However, due to its instability, successfully RL training is
challenging, especially in real-world systems where deep models and large
datasets are leveraged. In this paper, taking several large-scale translation
tasks as testbeds, we conduct a systematic study on how to train better NMT
models using reinforcement learning. We provide a comprehensive comparison of
several important factors (e.g., baseline reward, reward shaping) in RL
training. Furthermore, to fill in the gap that it remains unclear whether RL is
still beneficial when monolingual data is used, we propose a new method to
leverage RL to further boost the performance of NMT systems trained with
source/target monolingual data. By integrating all our findings, we obtain
competitive results on WMT14 English- German, WMT17 English-Chinese, and WMT17
Chinese-English translation tasks, especially setting a state-of-the-art
performance on WMT17 Chinese-English translation task.