---
layout: publication
title: 'Agentic-r1: Distilled Dual-strategy Reasoning'
authors: Du et al.
conference: Journal of Experimental &amp; Theoretical Artificial Intelligence
year: 2025
bibkey: du2025agentic
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.05707'}]
tags: [Training Techniques, Distillation, Alt, Agentic, Tools, Evaluation, Efficiency
    And Optimization, Fine Tuning, Datasets]
---
Current long chain-of-thought (long-CoT) models excel at mathematical reasoning but rely on slow and error-prone natural language traces. Tool-augmented agents address arithmetic via code execution, but often falter on complex logical tasks. We introduce a fine-tuning framework, DualDistill, that distills complementary reasoning strategies from multiple teachers into a unified student model. Using this approach, we train Agentic-R1, which dynamically selects the optimal strategy for each query, invoking tools for arithmetic and algorithmic problems, and using text-based reasoning for abstract ones. Our method improves accuracy across a range of tasks, including both computation-intensive and standard benchmarks, demonstrating the effectiveness of multi-strategy distillation in achieving robust and efficient reasoning. Our project is available at https://github.com/StigLidu/DualDistill