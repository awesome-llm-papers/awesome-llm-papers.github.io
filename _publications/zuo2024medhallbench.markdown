---
layout: publication
title: 'Medhallbench: A New Benchmark For Assessing Hallucination In Medical Large
  Language Models'
authors: Zuo Kaiwen, Jiang Yirui
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: zuo2024medhallbench
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.18947'}]
tags: [Training Techniques, EMNLP, Alt, Agentic, Tools, Evaluation, Reinforcement
    Learning, Applications, Datasets]
---
Medical Large Language Models (MLLMs) have demonstrated potential in
healthcare applications, yet their propensity for hallucinations -- generating
medically implausible or inaccurate information -- presents substantial risks
to patient care. This paper introduces MedHallBench, a comprehensive benchmark
framework for evaluating and mitigating hallucinations in MLLMs. Our
methodology integrates expert-validated medical case scenarios with established
medical databases to create a robust evaluation dataset. The framework employs
a sophisticated measurement system that combines automated ACHMI (Automatic
Caption Hallucination Measurement in Medical Imaging) scoring with rigorous
clinical expert evaluations and utilizes reinforcement learning methods to
achieve automatic annotation. Through an optimized reinforcement learning from
human feedback (RLHF) training pipeline specifically designed for medical
applications, MedHallBench enables thorough evaluation of MLLMs across diverse
clinical contexts while maintaining stringent accuracy standards. We conducted
comparative experiments involving various models, utilizing the benchmark to
establish a baseline for widely adopted large language models (LLMs). Our
findings indicate that ACHMI provides a more nuanced understanding of the
effects of hallucinations compared to traditional metrics, thereby highlighting
its advantages in hallucination assessment. This research establishes a
foundational framework for enhancing MLLMs' reliability in healthcare settings
and presents actionable strategies for addressing the critical challenge of AI
hallucinations in medical applications.