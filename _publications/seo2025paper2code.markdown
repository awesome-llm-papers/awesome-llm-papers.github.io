---
layout: publication
title: 'Paper2code: Automating Code Generation From Scientific Papers In Machine Learning'
authors: Minju Seo, Jinheon Baek, Seongyun Lee, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: seo2025paper2code
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/680aee7dcf67477f2c00ca96'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.17192'}]
tags: ["Llm For Code", "Tools"]
short_authors: Seo et al.
---
Despite the rapid growth of machine learning research, corresponding code implementations are often unavailable, making it slow and labor-intensive for researchers to reproduce results and build upon prior work. In the meantime, recent Large Language Models (LLMs) excel at understanding scientific documents and generating high-quality code. Inspired by this, we introduce PaperCoder, a multi-agent LLM framework that transforms machine learning papers into functional code repositories. PaperCoder operates in three stages: planning, where it constructs a high-level roadmap, designs the system architecture with diagrams, identifies file dependencies, and generates configuration files; analysis, which focuses on interpreting implementation-specific details; and generation, where modular, dependency-aware code is produced. Moreover, each phase is instantiated through a set of specialized agents designed to collaborate effectively across the pipeline. We then evaluate PaperCoder on generating code implementations from machine learning papers based on both model-based and human evaluations, specifically from the original paper authors, with author-released repositories as ground truth if available. Our results demonstrate the effectiveness of PaperCoder in creating high-quality, faithful implementations. Furthermore, it consistently shows strengths in the recently released PaperBench benchmark, surpassing strong baselines by substantial margins.

https://huggingface.co/discussions/paper/680aee7dcf67477f2c00ca96