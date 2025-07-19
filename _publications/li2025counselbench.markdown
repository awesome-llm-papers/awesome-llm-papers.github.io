---
layout: publication
title: 'Counselbench: A Large-scale Expert Evaluation And Adversarial Benchmark Of
  Large Language Models In Mental Health Counseling'
authors: Li et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: li2025counselbench
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.08584'}]
tags: [Datasets, EMNLP, GPT, Alt, Tools, Evaluation, Model Architecture, Reinforcement
    Learning, Security, Responsible AI]
---
Large language models (LLMs) are increasingly proposed for use in mental health support, yet their behavior in realistic counseling scenarios remains largely untested. We introduce CounselBench, a large-scale benchmark developed with 100 mental health professionals to evaluate and stress-test LLMs in single-turn counseling. The first component, CounselBench-EVAL, contains 2,000 expert evaluations of responses from GPT-4, LLaMA 3, Gemini, and online human therapists to real patient questions. Each response is rated along six clinically grounded dimensions, with written rationales and span-level annotations. We find that LLMs often outperform online human therapists in perceived quality, but experts frequently flag their outputs for safety concerns such as unauthorized medical advice. Follow-up experiments show that LLM judges consistently overrate model responses and overlook safety issues identified by human experts. To probe failure modes more directly, we construct CounselBench-Adv, an adversarial dataset of 120 expert-authored counseling questions designed to trigger specific model issues. Evaluation across 2,880 responses from eight LLMs reveals consistent, model-specific failure patterns. Together, CounselBench establishes a clinically grounded framework for benchmarking and improving LLM behavior in high-stakes mental health settings.