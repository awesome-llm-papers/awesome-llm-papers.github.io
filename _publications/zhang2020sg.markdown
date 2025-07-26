---
layout: publication
title: 'Sg-net: Syntax Guided Transformer For Language Representation'
authors: Zhuosheng Zhang, Yuwei Wu, Junru Zhou, Sufeng Duan, Hai Zhao, Rui Wang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: zhang2020sg
citations: 195
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.13915'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Zhang et al.
---
Understanding human language is one of the key themes of artificial
intelligence. For language representation, the capacity of effectively modeling
the linguistic knowledge from the detail-riddled and lengthy texts and getting
rid of the noises is essential to improve its performance. Traditional
attentive models attend to all words without explicit constraint, which results
in inaccurate concentration on some dispensable words. In this work, we propose
using syntax to guide the text modeling by incorporating explicit syntactic
constraints into attention mechanisms for better linguistically motivated word
representations. In detail, for self-attention network (SAN) sponsored
Transformer-based encoder, we introduce syntactic dependency of interest (SDOI)
design into the SAN to form an SDOI-SAN with syntax-guided self-attention.
Syntax-guided network (SG-Net) is then composed of this extra SDOI-SAN and the
SAN from the original Transformer encoder through a dual contextual
architecture for better linguistics inspired representation. The proposed
SG-Net is applied to typical Transformer encoders. Extensive experiments on
popular benchmark tasks, including machine reading comprehension, natural
language inference, and neural machine translation show the effectiveness of
the proposed SG-Net design.