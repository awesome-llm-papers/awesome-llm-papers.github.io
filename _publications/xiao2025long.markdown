---
layout: publication
title: 'Long Context Scaling: Divide And Conquer Via Multi-agent Question-driven Collaboration'
authors: Xiao et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: xiao2025long
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.20625'}]
tags: [RAG, Agentic, Tools, Evaluation, Datasets, Merging]
---
Processing long contexts has become a critical capability for modern large language models (LLMs). Existing works leverage agent-based divide-and-conquer methods for processing long contexts. But these methods face crucial limitations, including prohibitive accumulated latency and amplified information loss from excessive agent invocations, and the disruption of inherent textual dependencies by immoderate partitioning. In this paper, we propose a novel multi-agent framework XpandA (Expand-Agent) coupled with question-driven workflow and dynamic partitioning for robust long-context processing. XpandA overcomes these limitations through: 1) dynamic partitioning of long texts, which adaptively modulates the filling rate of context windows for input sequences of vastly varying lengths; 2) question-guided protocol to update flat information ensembles within centralized shared memory, constructing consistent inter-agent knowledge across partitions; and 3) selectively replaying specific partitions based on the state-tracking of question-information couples to promote the resolution of inverted-order structures across partitions (e.g., flashbacks). We perform a comprehensive evaluation of XpandA on multiple long-context benchmarks with length varying from 1k to 1M, demonstrating XpandA's feasibility for processing ultra-long sequences and its significant effectiveness in enhancing the long-context capabilities of various LLMs by achieving 20% improvements and 1.5x inference speedup over baselines of full-context, RAG and previous agent-based methods.