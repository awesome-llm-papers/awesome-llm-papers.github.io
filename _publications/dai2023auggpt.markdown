---
layout: publication
title: 'Auggpt: Leveraging Chatgpt For Text Data Augmentation'
authors: Haixing Dai, Zhengliang Liu, Wenxiong Liao, Xiaoke Huang, Yihan Cao, Zihao
  Wu, Lin Zhao, Shaochen Xu, Wei Liu, Ninghao Liu, Sheng Li, Dajiang Zhu, Hongmin
  Cai, Lichao Sun, Quanzheng Li, Dinggang Shen, Tianming Liu, Xiang Li
conference: Arxiv
year: 2023
bibkey: dai2023auggpt
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.13007'}]
tags: ["Few-Shot", "Training Techniques"]
short_authors: Dai et al.
---
Text data augmentation is an effective strategy for overcoming the challenge
of limited sample sizes in many natural language processing (NLP) tasks. This
challenge is especially prominent in the few-shot learning scenario, where the
data in the target domain is generally much scarcer and of lowered quality. A
natural and widely-used strategy to mitigate such challenges is to perform data
augmentation to better capture the data invariance and increase the sample
size. However, current text data augmentation methods either can't ensure the
correct labeling of the generated data (lacking faithfulness) or can't ensure
sufficient diversity in the generated data (lacking compactness), or both.
Inspired by the recent success of large language models, especially the
development of ChatGPT, which demonstrated improved language comprehension
abilities, in this work, we propose a text data augmentation approach based on
ChatGPT (named AugGPT). AugGPT rephrases each sentence in the training samples
into multiple conceptually similar but semantically different samples. The
augmented samples can then be used in downstream model training. Experiment
results on few-shot learning text classification tasks show the superior
performance of the proposed AugGPT approach over state-of-the-art text data
augmentation methods in terms of testing accuracy and distribution of the
augmented samples.