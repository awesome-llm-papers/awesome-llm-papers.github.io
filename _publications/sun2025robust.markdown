---
layout: publication
title: Robust Preference Optimization Via Dynamic Target Margins
authors: Sun et al.
conference: Signal Processing
year: 2025
bibkey: sun2025robust
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.03690'}]
tags: [Datasets, RAG, Training Techniques, Tools, Evaluation, ICASSP, Efficiency And
    Optimization, Reinforcement Learning, Applications, Responsible AI]
---
The alignment of Large Language Models (LLMs) is crucial for ensuring their safety and reliability in practical applications. Direct Preference Optimization (DPO) has emerged as an efficient method that directly optimizes models using preference pairs, significantly reducing resource demands. However, the effectiveness of DPO heavily depends on the data quality, which is frequently compromised by noise. In this work, we propose \\(\gamma\\)-PO, a dynamic target margin preference optimization algorithm that adjust reward margins at the pairwise level. By introducing instance-specific margin calibration, \\(\gamma\\)-PO strategically prioritizes high-confidence pairs (those demonstrating higher reward margins) while suppressing potential noise from ambiguous pairs. Moreover, \\(\gamma\\)-PO is a plug-and-play method, compatible with variants of DPO that rely on reward margin between preference pairs. Across benchmarks such as AlpacaEval2 and Arena-Hard, \\(\gamma\\)-PO achieves an average 4.4% improvement over other baselines, setting new benchmarks for state-of-the-art performance. Additionally, \\(\gamma\\)-PO requires minimal code changes and has a negligible impact on training efficiency, making it a robust solution for enhancing LLMs alignment. Our codes are available at \href\{https://github.com/sunjie279/gammaPO\}\{https://github.com/sunjie279/gammaPO\}.