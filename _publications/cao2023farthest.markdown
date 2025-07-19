---
layout: publication
title: Farthest Greedy Path Sampling For Two-shot Recommender Search
authors: Cao et al.
conference: Lecture Notes in Computer Science
year: 2023
bibkey: cao2023farthest
citations: 388
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.20705'}]
tags: [RAG, Tools, Evaluation, Model Architecture, Fine Tuning, Datasets]
---
Weight-sharing Neural Architecture Search (WS-NAS) provides an efficient
mechanism for developing end-to-end deep recommender models. However, in
complex search spaces, distinguishing between superior and inferior
architectures (or paths) is challenging. This challenge is compounded by the
limited coverage of the supernet and the co-adaptation of subnet weights, which
restricts the exploration and exploitation capabilities inherent to
weight-sharing mechanisms. To address these challenges, we introduce Farthest
Greedy Path Sampling (FGPS), a new path sampling strategy that balances path
quality and diversity. FGPS enhances path diversity to facilitate more
comprehensive supernet exploration, while emphasizing path quality to ensure
the effective identification and utilization of promising architectures. By
incorporating FGPS into a Two-shot NAS (TS-NAS) framework, we derive
high-performance architectures. Evaluations on three Click-Through Rate (CTR)
prediction benchmarks demonstrate that our approach consistently achieves
superior results, outperforming both manually designed and most NAS-based
models.