---
layout: publication
title: 'Mol-moe: Training Preference-guided Routers For Molecule Generation'
authors: Calanzone Diego, D'oro Pierluca, Bacon Pierre-luc
conference: Proceedings of the IEEE
year: 2025
bibkey: calanzone2025mol
citations: 186
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.05633'}]
tags: [Training Techniques, Agentic, Tools, Evaluation, Model Architecture, Time Series,
  Reinforcement Learning, Fine Tuning, Datasets]
---
Recent advances in language models have enabled framing molecule generation
as sequence modeling. However, existing approaches often rely on
single-objective reinforcement learning, limiting their applicability to
real-world drug design, where multiple competing properties must be optimized.
Traditional multi-objective reinforcement learning (MORL) methods require
costly retraining for each new objective combination, making rapid exploration
of trade-offs impractical. To overcome these limitations, we introduce Mol-MoE,
a mixture-of-experts (MoE) architecture that enables efficient test-time
steering of molecule generation without retraining. Central to our approach is
a preference-based router training objective that incentivizes the router to
combine experts in a way that aligns with user-specified trade-offs. This
provides improved flexibility in exploring the chemical property space at test
time, facilitating rapid trade-off exploration. Benchmarking against
state-of-the-art methods, we show that Mol-MoE achieves superior sample quality
and steerability.