---
layout: publication
title: 'On The Robustness Of Chatgpt: An Adversarial And Out-of-distribution Perspective'
authors: Jindong Wang, Xixu Hu, Wenxin Hou, Hao Chen, Runkai Zheng, Yidong Wang, Linyi
  Yang, Haojun Huang, Wei Ye, Xiubo Geng, Binxin Jiao, Yue Zhang, Xing Xie
conference: Arxiv
year: 2023
bibkey: wang2023robustness
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.12095'}]
tags: ["Security"]
short_authors: Wang et al.
---
ChatGPT is a recent chatbot service released by OpenAI and is receiving
increasing attention over the past few months. While evaluations of various
aspects of ChatGPT have been done, its robustness, i.e., the performance to
unexpected inputs, is still unclear to the public. Robustness is of particular
concern in responsible AI, especially for safety-critical applications. In this
paper, we conduct a thorough evaluation of the robustness of ChatGPT from the
adversarial and out-of-distribution (OOD) perspective. To do so, we employ the
AdvGLUE and ANLI benchmarks to assess adversarial robustness and the Flipkart
review and DDXPlus medical diagnosis datasets for OOD evaluation. We select
several popular foundation models as baselines. Results show that ChatGPT shows
consistent advantages on most adversarial and OOD classification and
translation tasks. However, the absolute performance is far from perfection,
which suggests that adversarial and OOD robustness remains a significant threat
to foundation models. Moreover, ChatGPT shows astounding performance in
understanding dialogue-related texts and we find that it tends to provide
informal suggestions for medical tasks instead of definitive answers. Finally,
we present in-depth discussions of possible research directions.