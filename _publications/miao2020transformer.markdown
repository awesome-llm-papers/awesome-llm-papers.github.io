---
layout: publication
title: Transformer-based Online Ctc/attention End-to-end Speech Recognition Architecture
authors: Haoran Miao, Gaofeng Cheng, Changfeng Gao, Pengyuan Zhang, Yonghong Yan
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: miao2020transformer
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.08290'}]
tags: ["ICASSP", "Model Architecture"]
short_authors: Miao et al.
---
Recently, Transformer has gained success in automatic speech recognition
(ASR) field. However, it is challenging to deploy a Transformer-based
end-to-end (E2E) model for online speech recognition. In this paper, we propose
the Transformer-based online CTC/attention E2E ASR architecture, which contains
the chunk self-attention encoder (chunk-SAE) and the monotonic truncated
attention (MTA) based self-attention decoder (SAD). Firstly, the chunk-SAE
splits the speech into isolated chunks. To reduce the computational cost and
improve the performance, we propose the state reuse chunk-SAE. Sencondly, the
MTA based SAD truncates the speech features monotonically and performs
attention on the truncated features. To support the online recognition, we
integrate the state reuse chunk-SAE and the MTA based SAD into online
CTC/attention architecture. We evaluate the proposed online models on the HKUST
Mandarin ASR benchmark and achieve a 23.66% character error rate (CER) with a
320 ms latency. Our online model yields as little as 0.19% absolute CER
degradation compared with the offline baseline, and achieves significant
improvement over our prior work on Long Short-Term Memory (LSTM) based online
E2E models.