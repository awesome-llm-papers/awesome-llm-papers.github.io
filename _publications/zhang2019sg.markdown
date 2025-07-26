---
layout: publication
title: 'Sg-net: Syntax-guided Machine Reading Comprehension'
authors: Zhuosheng Zhang, Yuwei Wu, Junru Zhou, Sufeng Duan, Hai Zhao, Rui Wang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: zhang2019sg
citations: 195
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.05147'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Zhang et al.
---
For machine reading comprehension, the capacity of effectively modeling the
linguistic knowledge from the detail-riddled and lengthy passages and getting
ride of the noises is essential to improve its performance. Traditional
attentive models attend to all words without explicit constraint, which results
in inaccurate concentration on some dispensable words. In this work, we propose
using syntax to guide the text modeling by incorporating explicit syntactic
constraints into attention mechanism for better linguistically motivated word
representations. In detail, for self-attention network (SAN) sponsored
Transformer-based encoder, we introduce syntactic dependency of interest (SDOI)
design into the SAN to form an SDOI-SAN with syntax-guided self-attention.
Syntax-guided network (SG-Net) is then composed of this extra SDOI-SAN and the
SAN from the original Transformer encoder through a dual contextual
architecture for better linguistics inspired representation. To verify its
effectiveness, the proposed SG-Net is applied to typical pre-trained language
model BERT which is right based on a Transformer encoder. Extensive experiments
on popular benchmarks including SQuAD 2.0 and RACE show that the proposed
SG-Net design helps achieve substantial performance improvement over strong
baselines.