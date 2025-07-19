---
layout: publication
title: Pretrained Hybrids With MAD Skills
authors: Roberts et al.
conference: Proceedings of the VLDB Endowment
year: 2024
bibkey: roberts2024pretrained
citations: 287
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.00894'}]
tags: [Training Techniques, GPT, Alt, Tools, Transformer, Model Architecture, Reinforcement
    Learning]
---
While Transformers underpin modern large language models (LMs), there is a
growing list of alternative architectures with new capabilities, promises, and
tradeoffs. This makes choosing the right LM architecture challenging.
Recently-proposed \\(\textit\{hybrid architectures\}\\) seek a best-of-all-worlds
approach that reaps the benefits of all architectures. Hybrid design is
difficult for two reasons: it requires manual expert-driven search, and new
hybrids must be trained from scratch. We propose \\(\textbf\{Manticore\}\\), a
framework that addresses these challenges. Manticore \\(\textit\{automates the
design of hybrid architectures\}\\) while reusing pretrained models to create
\\(\textit\{pretrained\}\\) hybrids. Our approach augments ideas from differentiable
Neural Architecture Search (NAS) by incorporating simple projectors that
translate features between pretrained blocks from different architectures. We
then fine-tune hybrids that combine pretrained models from different
architecture families -- such as the GPT series and Mamba -- end-to-end. With
Manticore, we enable LM selection without training multiple models, the
construction of pretrained hybrids from existing pretrained models, and the
ability to \\(\textit\{program\}\\) pretrained hybrids to have certain capabilities.
Manticore hybrids outperform existing manually-designed hybrids, achieve strong
performance on Long Range Arena (LRA) tasks, and can improve on pretrained
transformers and state space models.