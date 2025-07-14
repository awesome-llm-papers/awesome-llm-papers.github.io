---
layout: publication
title: 'Halle-control: Controlling Object Hallucination In Large Multimodal Models'
authors: Bohan Zhai, Shijia Yang, Chenfeng Xu, Sheng Shen, Kurt Keutzer, Chunyuan
  Li, Manling Li
conference: Arxiv
year: 2023
bibkey: bohan2023halle
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2310.01779v3'}]
tags: [Model Architecture, Multimodal Models, Evaluation, Datasets, GPT, RAG]
---
Current Large Multimodal Models (LMMs) achieve remarkable progress, yet there
remains significant uncertainty regarding their ability to accurately apprehend
visual details, that is, in performing detailed captioning. To address this, we
introduce \\(\textit\{CCEval\}\\), a GPT-4 assisted evaluation method for detailed
captioning. Interestingly, while LMMs demonstrate minimal object existence
hallucination in existing VQA benchmarks, our proposed evaluation reveals
continued susceptibility to such hallucinations. In this paper, we make the
first attempt to investigate such hallucination from different aspects,
including image resolution, the language decoder size, and instruction data
amount, quality, granularity. Our findings underscore the unwarranted inference
when the language description includes details at a finer object granularity
than what the vision module can ground or verify, thus inducing hallucination.
To control such hallucinations, we further attribute the reliability of
captioning to contextual knowledge (involving only contextually grounded
objects) and parametric knowledge (containing inferred objects by the model).
Thus, we introduce \\(\textit\{HallE-Control\}\\), a controllable LMM in terms of
\\(\textbf\{Hall\}\\)ucination in object \\(\textbf\{E\}\\)xistence. HallE-Control can
condition the captioning to shift between (i) exclusively depicting contextual
knowledge for grounded objects and (ii) blending it with parametric knowledge
to imagine inferred objects. Our method reduces hallucination by 44% compared
to LLaVA\\(_\{7B\}\\) and maintains the object coverage.