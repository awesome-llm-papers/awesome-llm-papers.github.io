---
layout: publication
title: 'Multimend: Multilingual Program Repair With Context Augmentation And Multi-hunk
  Patch Generation'
authors: Gharibi Reza, Sadreddini Mohammad Hadi, Fakhrahmad Seyed Mostafa
conference: 2019 IEEE/ACM 41st International Conference on Software Engineering (ICSE)
year: 2025
bibkey: gharibi2025multimend
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.16044'}]
tags: [Security, Model Architecture, Tools, Efficiency And Optimization, Evaluation,
  LLM For Code, LLM for Code, RAG, Transformer, Datasets, Reinforcement Learning]
---
Context: Bugs in code are inevitable and can lead to severe consequences,
ranging from security vulnerabilities to operational failures. Debugging
software remains challenging despite advances in testing and verification,
often requiring extensive manual effort. Learning-based automated program
repair (APR) has shown promise in reducing the time, effort, and cost of
manually fixing bugs. However, existing techniques face several challenges,
including language-dependent strategies, limited bug context utilization, and
difficulties in handling bugs that span multiple locations in the code.
  Objective: This paper introduces MultiMend, a learning-based APR approach
designed to improve repair performance on multiple programming languages with
language-independent context augmentation and multi-hunk patch generation.
  Method: MultiMend fine-tunes a pre-trained encoder-decoder transformer model
(CodeT5) to generate bug-fixing patches. It embeds source code lines and
applies retrieval-augmented generation to augment the buggy context with
relevant lines during patch generation. The approach systematically constructs
patches for multi-hunk bugs to reduce the needed patch validations. We evaluate
MultiMend on four benchmarks with four programming languages and compare it
with state-of-the-art methods.
  Results: Experimental results show that MultiMend achieves competitive
effectiveness and efficiency against compared tools. Across all benchmarks,
MultiMend fixes 2,077 bugs, of which 1,455 are identical to the developer's
patch, and 106 are for multi-hunk bugs. Both context augmentation and
multi-hunk patch generation positively contribute to the results.
  Conclusion: MultiMend shows promising performance across benchmarks. The
findings highlight its applicability to real-world software maintenance and its
potential to reduce manual debugging efforts.