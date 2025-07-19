---
layout: publication
title: Memory And Bandwidth Are All You Need For Fully Sharded Data Parallel
authors: Wang et al.
conference: Proceedings of the VLDB Endowment
year: 2025
bibkey: wang2025memory
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.03655'}]
tags: [Training Techniques, Prompting, Evaluation, Transformer, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning]
---
Transformer models have revolutionized a wide spectrum of disciplines,
especially in language processing. The recent success has proven that model
size scalability is crucial for achieving superior performance metrics.
However, training large transformer models is challenging even on modern
hardware with powerful GPUs and high-speed interconnects. Existing studies
primarily focus on optimizing model training distribution strategies to
minimize memory footprint and enhance training speed, often overlooking the
scalability challenges related to model size and hardware constraints. To
address this oversight, we thoroughly investigate computational, memory, and
network demands of training large transformers using the Fully Sharded Data
Parallel (FSDP) distributed strategy across different hardware clusters. We
explore the intricate relationships between model size and hardware setups to
identify configurations that ensure maximum model and hardware efficiency,
effective sequence length management, and optimal training throughput. A
significant finding of our study is the critical interplay of the cluster's
connection bandwidth and GPU memory size compared to the computational
performance of GPUs. This interplay limits training efficiency, underscoring
the role of both hardware characteristics as a possible bottleneck. By
integrating theoretical analysis with simulations and empirical tests, we
demonstrate how hardware limitations affect training efficacy, identifying key
hardware thresholds and the impact of network connectivity. Our findings prompt
a reassessment of training strategies guiding users on the way to finding
hardware-optimal FSDP configurations, enhancing training efficiency for
large-scale transformer models.