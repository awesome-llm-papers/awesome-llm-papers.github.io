---
layout: publication
title: Deep Session Interest Network For Click-through Rate Prediction
authors: Yufei Feng, Fuyu Lv, Weichen Shen, Menghan Wang, Fei Sun, Yu Zhu, Keping
  Yang
conference: Proceedings of the Twenty-Eighth International Joint Conference on Artificial
  Intelligence
year: 2019
bibkey: feng2019deep
citations: 237
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.06482'}]
tags: ["Applications", "IJCAI", "Model Architecture"]
short_authors: Feng et al.
---
Click-Through Rate (CTR) prediction plays an important role in many
industrial applications, such as online advertising and recommender systems.
How to capture users' dynamic and evolving interests from their behavior
sequences remains a continuous research topic in the CTR prediction. However,
most existing studies overlook the intrinsic structure of the sequences: the
sequences are composed of sessions, where sessions are user behaviors separated
by their occurring time. We observe that user behaviors are highly homogeneous
in each session, and heterogeneous cross sessions. Based on this observation,
we propose a novel CTR model named Deep Session Interest Network (DSIN) that
leverages users' multiple historical sessions in their behavior sequences. We
first use self-attention mechanism with bias encoding to extract users'
interests in each session. Then we apply Bi-LSTM to model how users' interests
evolve and interact among sessions. Finally, we employ the local activation
unit to adaptively learn the influences of various session interests on the
target item. Experiments are conducted on both advertising and production
recommender datasets and DSIN outperforms other state-of-the-art models on both
datasets.